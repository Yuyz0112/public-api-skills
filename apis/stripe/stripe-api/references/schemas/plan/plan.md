# plan

You can now model subscriptions more flexibly using the [Prices API](https://api.stripe.com#prices). It replaces the Plans API and is backwards compatible to simplify your migration.

Plans define the base price, currency, and billing cycle for recurring purchases of products.
[Products](https://api.stripe.com#products) help you track inventory or provisioning, and plans help you track pricing. Different physical goods or levels of service should be represented by products, and pricing options should be represented by plans. This approach lets you change prices without having to change your provisioning scheme.

For example, you might have a single "gold" product that has plans for $10/month, $100/year, €9/month, and €90/year.

Related guides: [Set up a subscription](https://docs.stripe.com/billing/subscriptions/set-up-subscription) and more about [products and prices](https://docs.stripe.com/products-prices/overview).

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `active` | boolean | Yes | Whether the plan can be used for new purchases. |
| `amount` | integer | No | The unit amount in cents (or local equivalent) to be charged, represented as a whole integer if possible. Only set if `billing_scheme=per_unit`. |
| `amount_decimal` | string (decimal) | No | The unit amount in cents (or local equivalent) to be charged, represented as a decimal string with at most 12 decimal places. Only set if `billing_scheme=per_unit`. |
| `billing_scheme` | enum: per_unit, tiered | Yes | Describes how to compute the price per period. Either `per_unit` or `tiered`. `per_unit` indicates that the fixed amount (specified in `amount`) will be charged per unit in `quantity` (for plans with `usage_type=licensed`), or per unit of total usage (for plans with `usage_type=metered`). `tiered` indicates that the unit pricing will be computed using a tiering strategy as defined using the `tiers` and `tiers_mode` attributes. |
| `created` | integer (unix-time) | Yes | Time at which the object was created. Measured in seconds since the Unix epoch. |
| `currency` | string (currency) | Yes | Three-letter [ISO currency code](https://www.iso.org/iso-4217-currency-codes.html), in lowercase. Must be a [supported currency](https://stripe.com/docs/currencies). |
| `id` | string | Yes | Unique identifier for the object. |
| `interval` | enum: day, month, week... | Yes | The frequency at which a subscription is billed. One of `day`, `week`, `month` or `year`. |
| `interval_count` | integer | Yes | The number of intervals (specified in the `interval` attribute) between subscription billings. For example, `interval=month` and `interval_count=3` bills every 3 months. |
| `livemode` | boolean | Yes | Has the value `true` if the object exists in live mode or the value `false` if the object exists in test mode. |
| `metadata` | object | No | Set of [key-value pairs](https://docs.stripe.com/api/metadata) that you can attach to an object. This can be useful for storing additional information about the object in a structured format. |
| `meter` | string | No | The meter tracking the usage of a metered price |
| `nickname` | string | No | A brief description of the plan, hidden from customers. |
| `object` | enum: plan | Yes | String representing the object's type. Objects of the same type share the same value. |
| `product` | any | No | The product whose pricing this plan determines. |
| `tiers` | plan_tier[] | No | Each element represents a pricing tier. This parameter requires `billing_scheme` to be set to `tiered`. See also the documentation for `billing_scheme`. |
| `tiers_mode` | enum: graduated, volume | No | Defines if the tiering price should be `graduated` or `volume` based. In `volume`-based tiering, the maximum quantity within a period determines the per unit price. In `graduated` tiering, pricing can change as the quantity grows. |
| `transform_usage` | any | No | Apply a transformation to the reported usage or set quantity before computing the amount billed. Cannot be combined with `tiers`. |
| `trial_period_days` | integer | No | Default number of trial days when subscribing a customer to this plan using [`trial_from_plan=true`](https://docs.stripe.com/api#create_subscription-trial_from_plan). |
| `usage_type` | enum: licensed, metered | Yes | Configures how the quantity per period should be determined. Can be either `metered` or `licensed`. `licensed` automatically bills the `quantity` set when adding it to a subscription. `metered` aggregates the total usage based on usage records. Defaults to `licensed`. |


# subscription_item

Subscription items allow you to create customer subscriptions with more than
one plan, making it easy to represent complex billing relationships.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `billing_thresholds` | any | No | Define thresholds at which an invoice will be sent, and the related subscription advanced to a new billing period |
| `created` | integer | Yes | Time at which the object was created. Measured in seconds since the Unix epoch. |
| `current_period_end` | integer (unix-time) | Yes | The end time of this subscription item's current billing period. |
| `current_period_start` | integer (unix-time) | Yes | The start time of this subscription item's current billing period. |
| `discounts` | any[] | Yes | The discounts applied to the subscription item. Subscription item discounts are applied before subscription discounts. Use `expand[]=discounts` to expand each discount. |
| `id` | string | Yes | Unique identifier for the object. |
| `metadata` | object | Yes | Set of [key-value pairs](https://docs.stripe.com/api/metadata) that you can attach to an object. This can be useful for storing additional information about the object in a structured format. |
| `object` | enum: subscription_item | Yes | String representing the object's type. Objects of the same type share the same value. |
| `price` | [price](price.md) | Yes |  |
| `quantity` | integer | No | The [quantity](https://docs.stripe.com/subscriptions/quantities) of the plan to which the customer should be subscribed. |
| `subscription` | string | Yes | The `subscription` this `subscription_item` belongs to. |
| `tax_rates` | tax_rate[] | No | The tax rates which apply to this `subscription_item`. When set, the `default_tax_rates` on the subscription do not apply to this `subscription_item`. |


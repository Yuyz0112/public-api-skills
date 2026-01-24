# subscription_schedule_configuration_item

A phase item describes the price and quantity of a phase.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `billing_thresholds` | any | No | Define thresholds at which an invoice will be sent, and the related subscription advanced to a new billing period |
| `discounts` | discounts_resource_stackable_discount[] | Yes | The discounts applied to the subscription item. Subscription item discounts are applied before subscription discounts. Use `expand[]=discounts` to expand each discount. |
| `metadata` | object | No | Set of [key-value pairs](https://docs.stripe.com/api/metadata) that you can attach to an item. Metadata on this item will update the underlying subscription item's `metadata` when the phase is entered. |
| `price` | any | Yes | ID of the price to which the customer should be subscribed. |
| `quantity` | integer | No | Quantity of the plan to which the customer should be subscribed. |
| `tax_rates` | tax_rate[] | No | The tax rates which apply to this `phase_item`. When set, the `default_tax_rates` on the phase do not apply to this `phase_item`. |


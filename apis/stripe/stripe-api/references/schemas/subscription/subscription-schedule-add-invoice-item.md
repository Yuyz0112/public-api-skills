# subscription_schedule_add_invoice_item

An Add Invoice Item describes the prices and quantities that will be added as pending invoice items when entering a phase.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `discounts` | discounts_resource_stackable_discount[] | Yes | The stackable discounts that will be applied to the item. |
| `metadata` | object | No | Set of [key-value pairs](https://docs.stripe.com/api/metadata) that you can attach to an object. This can be useful for storing additional information about the object in a structured format. |
| `period` | [subscription_schedule_add_invoice_item_period](subscription-schedule-add-invoice-item-period.md) | Yes |  |
| `price` | any | Yes | ID of the price used to generate the invoice item. |
| `quantity` | integer | No | The quantity of the invoice item. |
| `tax_rates` | tax_rate[] | No | The tax rates which apply to the item. When set, the `default_tax_rates` do not apply to this item. |


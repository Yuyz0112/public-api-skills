# credit_note_line_item

The credit note line item object

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `amount` | integer | Yes | The integer amount in cents (or local equivalent) representing the gross amount being credited for this line item, excluding (exclusive) tax and discounts. |
| `description` | string | No | Description of the item being credited. |
| `discount_amount` | integer | Yes | The integer amount in cents (or local equivalent) representing the discount being credited for this line item. |
| `discount_amounts` | discounts_resource_discount_amount[] | Yes | The amount of discount calculated per discount for this line item |
| `id` | string | Yes | Unique identifier for the object. |
| `invoice_line_item` | string | No | ID of the invoice line item being credited |
| `livemode` | boolean | Yes | Has the value `true` if the object exists in live mode or the value `false` if the object exists in test mode. |
| `object` | enum: credit_note_line_item | Yes | String representing the object's type. Objects of the same type share the same value. |
| `pretax_credit_amounts` | credit_notes_pretax_credit_amount[] | Yes | The pretax credit amounts (ex: discount, credit grants, etc) for this line item. |
| `quantity` | integer | No | The number of units of product being credited. |
| `tax_rates` | tax_rate[] | Yes | The tax rates which apply to the line item. |
| `taxes` | billing_bill_resource_invoicing_taxes_tax[] | No | The tax information of the line item. |
| `type` | enum: custom_line_item, invoice_line_item | Yes | The type of the credit note line item, one of `invoice_line_item` or `custom_line_item`. When the type is `invoice_line_item` there is an additional `invoice_line_item` property on the resource the value of which is the id of the credited line item on the invoice. |
| `unit_amount` | integer | No | The cost of each unit of product being credited. |
| `unit_amount_decimal` | string (decimal) | No | Same as `unit_amount`, but contains a decimal value with at most 12 decimal places. |


# line_items_tax_amount

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `amount` | integer | Yes | Amount of tax applied for this rate. |
| `rate` | [tax_rate](tax-rate.md) | Yes |  |
| `taxability_reason` | enum: customer_exempt, not_collecting, not_subject_to_tax... | No | The reasoning behind this tax, for example, if the product is tax exempt. The possible values for this field may be extended as new tax rules are supported. |
| `taxable_amount` | integer | No | The amount on which tax is calculated, in cents (or local equivalent). |


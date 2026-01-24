# billing_bill_resource_invoicing_taxes_tax

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `amount` | integer | Yes | The amount of the tax, in cents (or local equivalent). |
| `tax_behavior` | enum: exclusive, inclusive | Yes | Whether this tax is inclusive or exclusive. |
| `tax_rate_details` | any | No | Additional details about the tax rate. Only present when `type` is `tax_rate_details`. |
| `taxability_reason` | enum: customer_exempt, not_available, not_collecting... | Yes | The reasoning behind this tax, for example, if the product is tax exempt. The possible values for this field may be extended as new tax rules are supported. |
| `taxable_amount` | integer | No | The amount on which tax is calculated, in cents (or local equivalent). |
| `type` | enum: tax_rate_details | Yes | The type of tax information. |


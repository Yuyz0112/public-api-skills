# tax_product_resource_tax_breakdown

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `amount` | integer | Yes | The amount of tax, in the [smallest currency unit](https://docs.stripe.com/currencies#zero-decimal). |
| `inclusive` | boolean | Yes | Specifies whether the tax amount is included in the line item amount. |
| `tax_rate_details` | [tax_product_resource_tax_rate_details](tax-product-resource-tax-rate-details.md) | Yes |  |
| `taxability_reason` | enum: customer_exempt, not_collecting, not_subject_to_tax... | Yes | The reasoning behind this tax, for example, if the product is tax exempt. We might extend the possible values for this field to support new tax rules. |
| `taxable_amount` | integer | Yes | The amount on which tax is calculated, in the [smallest currency unit](https://docs.stripe.com/currencies#zero-decimal). |


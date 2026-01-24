# tax_product_resource_line_item_tax_breakdown

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `amount` | integer | Yes | The amount of tax, in the [smallest currency unit](https://docs.stripe.com/currencies#zero-decimal). |
| `jurisdiction` | [tax_product_resource_jurisdiction](tax-product-resource-jurisdiction.md) | Yes |  |
| `sourcing` | enum: destination, origin | Yes | Indicates whether the jurisdiction was determined by the origin (merchant's address) or destination (customer's address). |
| `tax_rate_details` | any | No | Details regarding the rate for this tax. This field will be `null` when the tax is not imposed, for example if the product is exempt from tax. |
| `taxability_reason` | enum: customer_exempt, not_collecting, not_subject_to_tax... | Yes | The reasoning behind this tax, for example, if the product is tax exempt. The possible values for this field may be extended as new tax rules are supported. |
| `taxable_amount` | integer | Yes | The amount on which tax is calculated, in the [smallest currency unit](https://docs.stripe.com/currencies#zero-decimal). |


# tax.calculation

A Tax Calculation allows you to calculate the tax to collect from your customer.

Related guide: [Calculate tax in your custom payment flow](https://docs.stripe.com/tax/custom)

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `amount_total` | integer | Yes | Total amount after taxes in the [smallest currency unit](https://docs.stripe.com/currencies#zero-decimal). |
| `currency` | string | Yes | Three-letter [ISO currency code](https://www.iso.org/iso-4217-currency-codes.html), in lowercase. Must be a [supported currency](https://stripe.com/docs/currencies). |
| `customer` | string | No | The ID of an existing [Customer](https://docs.stripe.com/api/customers/object) used for the resource. |
| `customer_details` | [tax_product_resource_customer_details](tax-product-resource-customer-details.md) | Yes |  |
| `expires_at` | integer (unix-time) | No | Timestamp of date at which the tax calculation will expire. |
| `id` | string | No | Unique identifier for the calculation. |
| `line_items` | object | No | The list of items the customer is purchasing. |
| `livemode` | boolean | Yes | Has the value `true` if the object exists in live mode or the value `false` if the object exists in test mode. |
| `object` | enum: tax.calculation | Yes | String representing the object's type. Objects of the same type share the same value. |
| `ship_from_details` | any | No | The details of the ship from location, such as the address. |
| `shipping_cost` | any | No | The shipping cost details for the calculation. |
| `tax_amount_exclusive` | integer | Yes | The amount of tax to be collected on top of the line item prices. |
| `tax_amount_inclusive` | integer | Yes | The amount of tax already included in the line item prices. |
| `tax_breakdown` | tax_product_resource_tax_breakdown[] | Yes | Breakdown of individual tax amounts that add up to the total. |
| `tax_date` | integer (unix-time) | Yes | Timestamp of date at which the tax rules and rates in effect applies for the calculation. |

## Nested Fields

### `line_items`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `data` | tax.calculation_line_item[] | Yes | Details about each object. |
| `has_more` | boolean | Yes | True if this list has another page of items after this one that can be fetched. |
| `object` | enum: list | Yes | String representing the object's type. Objects of the same type share the same value. Always has the value `list`. |
| `url` | string | Yes | The URL where this list can be accessed. |


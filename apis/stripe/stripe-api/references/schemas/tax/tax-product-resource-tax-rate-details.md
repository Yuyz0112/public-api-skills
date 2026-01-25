# tax_product_resource_tax_rate_details

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `country` | string | No | Two-letter country code ([ISO 3166-1 alpha-2](https://en.wikipedia.org/wiki/ISO_3166-1_alpha-2)). |
| `flat_amount` | any | No | The amount of the tax rate when the `rate_type` is `flat_amount`. Tax rates with `rate_type` `percentage` can vary based on the transaction, resulting in this field being `null`. This field exposes the amount and currency of the flat tax rate. |
| `percentage_decimal` | string | Yes | The tax rate percentage as a string. For example, 8.5% is represented as `"8.5"`. |
| `rate_type` | enum: flat_amount, percentage | No | Indicates the type of tax rate applied to the taxable amount. This value can be `null` when no tax applies to the location. This field is only present for TaxRates created by Stripe Tax. |
| `state` | string | No | State, county, province, or region ([ISO 3166-2](https://en.wikipedia.org/wiki/ISO_3166-2)). |
| `tax_type` | enum: amusement_tax, communications_tax, gst... | No | The tax type, such as `vat` or `sales_tax`. |


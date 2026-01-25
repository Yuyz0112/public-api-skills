# tax.transaction

A Tax Transaction records the tax collected from or refunded to your customer.

Related guide: [Calculate tax in your custom payment flow](https://docs.stripe.com/tax/custom#tax-transaction)

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `created` | integer (unix-time) | Yes | Time at which the object was created. Measured in seconds since the Unix epoch. |
| `currency` | string | Yes | Three-letter [ISO currency code](https://www.iso.org/iso-4217-currency-codes.html), in lowercase. Must be a [supported currency](https://stripe.com/docs/currencies). |
| `customer` | string | No | The ID of an existing [Customer](https://docs.stripe.com/api/customers/object) used for the resource. |
| `customer_details` | [tax_product_resource_customer_details](tax-product-resource-customer-details.md) | Yes |  |
| `id` | string | Yes | Unique identifier for the transaction. |
| `line_items` | object | No | The tax collected or refunded, by line item. |
| `livemode` | boolean | Yes | Has the value `true` if the object exists in live mode or the value `false` if the object exists in test mode. |
| `metadata` | object | No | Set of [key-value pairs](https://docs.stripe.com/api/metadata) that you can attach to an object. This can be useful for storing additional information about the object in a structured format. |
| `object` | enum: tax.transaction | Yes | String representing the object's type. Objects of the same type share the same value. |
| `posted_at` | integer (unix-time) | Yes | The Unix timestamp representing when the tax liability is assumed or reduced. |
| `reference` | string | Yes | A custom unique identifier, such as 'myOrder_123'. |
| `reversal` | any | No | If `type=reversal`, contains information about what was reversed. |
| `ship_from_details` | any | No | The details of the ship from location, such as the address. |
| `shipping_cost` | any | No | The shipping cost details for the transaction. |
| `tax_date` | integer (unix-time) | Yes | Timestamp of date at which the tax rules and rates in effect applies for the calculation. |
| `type` | enum: reversal, transaction | Yes | If `reversal`, this transaction reverses an earlier transaction. |

## Nested Fields

### `line_items`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `data` | tax.transaction_line_item[] | Yes | Details about each object. |
| `has_more` | boolean | Yes | True if this list has another page of items after this one that can be fetched. |
| `object` | enum: list | Yes | String representing the object's type. Objects of the same type share the same value. Always has the value `list`. |
| `url` | string | Yes | The URL where this list can be accessed. |


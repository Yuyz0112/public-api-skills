# tax.transaction_line_item

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `amount` | integer | Yes | The line item amount in the [smallest currency unit](https://docs.stripe.com/currencies#zero-decimal). If `tax_behavior=inclusive`, then this amount includes taxes. Otherwise, taxes were calculated on top of this amount. |
| `amount_tax` | integer | Yes | The amount of tax calculated for this line item, in the [smallest currency unit](https://docs.stripe.com/currencies#zero-decimal). |
| `id` | string | Yes | Unique identifier for the object. |
| `livemode` | boolean | Yes | Has the value `true` if the object exists in live mode or the value `false` if the object exists in test mode. |
| `metadata` | object | No | Set of [key-value pairs](https://docs.stripe.com/api/metadata) that you can attach to an object. This can be useful for storing additional information about the object in a structured format. |
| `object` | enum: tax.transaction_line_item | Yes | String representing the object's type. Objects of the same type share the same value. |
| `product` | string | No | The ID of an existing [Product](https://docs.stripe.com/api/products/object). |
| `quantity` | integer | Yes | The number of units of the item being purchased. For reversals, this is the quantity reversed. |
| `reference` | string | Yes | A custom identifier for this line item in the transaction. |
| `reversal` | any | No | If `type=reversal`, contains information about what was reversed. |
| `tax_behavior` | enum: exclusive, inclusive | Yes | Specifies whether the `amount` includes taxes. If `tax_behavior=inclusive`, then the amount includes taxes. |
| `tax_code` | string | Yes | The [tax code](https://docs.stripe.com/tax/tax-categories) ID used for this resource. |
| `type` | enum: reversal, transaction | Yes | If `reversal`, this line item reverses an earlier transaction. |


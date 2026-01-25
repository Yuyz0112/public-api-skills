# tax_product_resource_tax_transaction_shipping_cost

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `amount` | integer | Yes | The shipping amount in the [smallest currency unit](https://docs.stripe.com/currencies#zero-decimal). If `tax_behavior=inclusive`, then this amount includes taxes. Otherwise, taxes were calculated on top of this amount. |
| `amount_tax` | integer | Yes | The amount of tax calculated for shipping, in the [smallest currency unit](https://docs.stripe.com/currencies#zero-decimal). |
| `shipping_rate` | string | No | The ID of an existing [ShippingRate](https://docs.stripe.com/api/shipping_rates/object). |
| `tax_behavior` | enum: exclusive, inclusive | Yes | Specifies whether the `amount` includes taxes. If `tax_behavior=inclusive`, then the amount includes taxes. |
| `tax_code` | string | Yes | The [tax code](https://docs.stripe.com/tax/tax-categories) ID used for shipping. |


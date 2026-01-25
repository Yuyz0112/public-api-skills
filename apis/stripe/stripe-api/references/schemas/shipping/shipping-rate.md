# shipping_rate

Shipping rates describe the price of shipping presented to your customers and
applied to a purchase. For more information, see [Charge for shipping](https://docs.stripe.com/payments/during-payment/charge-shipping).

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `active` | boolean | Yes | Whether the shipping rate can be used for new purchases. Defaults to `true`. |
| `created` | integer (unix-time) | Yes | Time at which the object was created. Measured in seconds since the Unix epoch. |
| `delivery_estimate` | any | No | The estimated range for how long shipping will take, meant to be displayable to the customer. This will appear on CheckoutSessions. |
| `display_name` | string | No | The name of the shipping rate, meant to be displayable to the customer. This will appear on CheckoutSessions. |
| `fixed_amount` | [shipping_rate_fixed_amount](shipping-rate-fixed-amount.md) | No |  |
| `id` | string | Yes | Unique identifier for the object. |
| `livemode` | boolean | Yes | Has the value `true` if the object exists in live mode or the value `false` if the object exists in test mode. |
| `metadata` | object | Yes | Set of [key-value pairs](https://docs.stripe.com/api/metadata) that you can attach to an object. This can be useful for storing additional information about the object in a structured format. |
| `object` | enum: shipping_rate | Yes | String representing the object's type. Objects of the same type share the same value. |
| `tax_behavior` | enum: exclusive, inclusive, unspecified | No | Specifies whether the rate is considered inclusive of taxes or exclusive of taxes. One of `inclusive`, `exclusive`, or `unspecified`. |
| `tax_code` | any | No | A [tax code](https://docs.stripe.com/tax/tax-categories) ID. The Shipping tax code is `txcd_92010001`. |
| `type` | enum: fixed_amount | Yes | The type of calculation to use on the shipping rate. |


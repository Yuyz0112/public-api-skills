# review

Reviews can be used to supplement automated fraud detection with human expertise.

Learn more about [Radar](/radar) and reviewing payments
[here](https://docs.stripe.com/radar/reviews).

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `billing_zip` | string | No | The ZIP or postal code of the card used, if applicable. |
| `charge` | any | No | The charge associated with this review. |
| `closed_reason` | enum: acknowledged, approved, canceled... | No | The reason the review was closed, or null if it has not yet been closed. One of `approved`, `refunded`, `refunded_as_fraud`, `disputed`, `redacted`, `canceled`, `payment_never_settled`, or `acknowledged`. |
| `created` | integer (unix-time) | Yes | Time at which the object was created. Measured in seconds since the Unix epoch. |
| `id` | string | Yes | Unique identifier for the object. |
| `ip_address` | string | No | The IP address where the payment originated. |
| `ip_address_location` | any | No | Information related to the location of the payment. Note that this information is an approximation and attempts to locate the nearest population center - it should not be used to determine a specific address. |
| `livemode` | boolean | Yes | Has the value `true` if the object exists in live mode or the value `false` if the object exists in test mode. |
| `object` | enum: review | Yes | String representing the object's type. Objects of the same type share the same value. |
| `open` | boolean | Yes | If `true`, the review needs action. |
| `opened_reason` | enum: manual, rule | Yes | The reason the review was opened. One of `rule` or `manual`. |
| `payment_intent` | any | No | The PaymentIntent ID associated with this review, if one exists. |
| `reason` | string | Yes | The reason the review is currently open or closed. One of `rule`, `manual`, `approved`, `refunded`, `refunded_as_fraud`, `disputed`, `redacted`, `canceled`, `payment_never_settled`, or `acknowledged`. |
| `session` | any | No | Information related to the browsing session of the user who initiated the payment. |


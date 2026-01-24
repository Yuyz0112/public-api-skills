# application_fee

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `account` | any | Yes | ID of the Stripe account this fee was taken from. |
| `amount` | integer | Yes | Amount earned, in cents (or local equivalent). |
| `amount_refunded` | integer | Yes | Amount in cents (or local equivalent) refunded (can be less than the amount attribute on the fee if a partial refund was issued) |
| `application` | any | Yes | ID of the Connect application that earned the fee. |
| `balance_transaction` | any | No | Balance transaction that describes the impact of this collected application fee on your account balance (not including refunds). |
| `charge` | any | Yes | ID of the charge that the application fee was taken from. |
| `created` | integer (unix-time) | Yes | Time at which the object was created. Measured in seconds since the Unix epoch. |
| `currency` | string (currency) | Yes | Three-letter [ISO currency code](https://www.iso.org/iso-4217-currency-codes.html), in lowercase. Must be a [supported currency](https://stripe.com/docs/currencies). |
| `fee_source` | any | No | Polymorphic source of the application fee. Includes the ID of the object the application fee was created from. |
| `id` | string | Yes | Unique identifier for the object. |
| `livemode` | boolean | Yes | Has the value `true` if the object exists in live mode or the value `false` if the object exists in test mode. |
| `object` | enum: application_fee | Yes | String representing the object's type. Objects of the same type share the same value. |
| `originating_transaction` | any | No | ID of the corresponding charge on the platform account, if this fee was the result of a charge using the `destination` parameter. |
| `refunded` | boolean | Yes | Whether the fee has been fully refunded. If the fee is only partially refunded, this attribute will still be false. |
| `refunds` | object | Yes | A list of refunds that have been applied to the fee. |

## Nested Fields

### `refunds`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `data` | fee_refund[] | Yes | Details about each object. |
| `has_more` | boolean | Yes | True if this list has another page of items after this one that can be fetched. |
| `object` | enum: list | Yes | String representing the object's type. Objects of the same type share the same value. Always has the value `list`. |
| `url` | string | Yes | The URL where this list can be accessed. |


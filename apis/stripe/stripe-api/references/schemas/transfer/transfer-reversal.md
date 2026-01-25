# transfer_reversal

[Stripe Connect](https://docs.stripe.com/connect) platforms can reverse transfers made to a
connected account, either entirely or partially, and can also specify whether
to refund any related application fees. Transfer reversals add to the
platform's balance and subtract from the destination account's balance.

Reversing a transfer that was made for a [destination
charge](/docs/connect/destination-charges) is allowed only up to the amount of
the charge. It is possible to reverse a
[transfer_group](https://docs.stripe.com/connect/separate-charges-and-transfers#transfer-options)
transfer only if the destination account has enough balance to cover the
reversal.

Related guide: [Reverse transfers](https://docs.stripe.com/connect/separate-charges-and-transfers#reverse-transfers)

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `amount` | integer | Yes | Amount, in cents (or local equivalent). |
| `balance_transaction` | any | No | Balance transaction that describes the impact on your account balance. |
| `created` | integer (unix-time) | Yes | Time at which the object was created. Measured in seconds since the Unix epoch. |
| `currency` | string (currency) | Yes | Three-letter [ISO currency code](https://www.iso.org/iso-4217-currency-codes.html), in lowercase. Must be a [supported currency](https://stripe.com/docs/currencies). |
| `destination_payment_refund` | any | No | Linked payment refund for the transfer reversal. |
| `id` | string | Yes | Unique identifier for the object. |
| `metadata` | object | No | Set of [key-value pairs](https://docs.stripe.com/api/metadata) that you can attach to an object. This can be useful for storing additional information about the object in a structured format. |
| `object` | enum: transfer_reversal | Yes | String representing the object's type. Objects of the same type share the same value. |
| `source_refund` | any | No | ID of the refund responsible for the transfer reversal. |
| `transfer` | any | Yes | ID of the transfer that was reversed. |


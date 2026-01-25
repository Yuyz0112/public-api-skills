# transfer

A `Transfer` object is created when you move funds between Stripe accounts as
part of Connect.

Before April 6, 2017, transfers also represented movement of funds from a
Stripe account to a card or bank account. This behavior has since been split
out into a [Payout](https://api.stripe.com#payout_object) object, with corresponding payout endpoints. For more
information, read about the
[transfer/payout split](https://docs.stripe.com/transfer-payout-split).

Related guide: [Creating separate charges and transfers](https://docs.stripe.com/connect/separate-charges-and-transfers)

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `amount` | integer | Yes | Amount in cents (or local equivalent) to be transferred. |
| `amount_reversed` | integer | Yes | Amount in cents (or local equivalent) reversed (can be less than the amount attribute on the transfer if a partial reversal was issued). |
| `balance_transaction` | any | No | Balance transaction that describes the impact of this transfer on your account balance. |
| `created` | integer (unix-time) | Yes | Time that this record of the transfer was first created. |
| `currency` | string (currency) | Yes | Three-letter [ISO currency code](https://www.iso.org/iso-4217-currency-codes.html), in lowercase. Must be a [supported currency](https://stripe.com/docs/currencies). |
| `description` | string | No | An arbitrary string attached to the object. Often useful for displaying to users. |
| `destination` | any | No | ID of the Stripe account the transfer was sent to. |
| `destination_payment` | any | No | If the destination is a Stripe account, this will be the ID of the payment that the destination account received for the transfer. |
| `id` | string | Yes | Unique identifier for the object. |
| `livemode` | boolean | Yes | Has the value `true` if the object exists in live mode or the value `false` if the object exists in test mode. |
| `metadata` | object | Yes | Set of [key-value pairs](https://docs.stripe.com/api/metadata) that you can attach to an object. This can be useful for storing additional information about the object in a structured format. |
| `object` | enum: transfer | Yes | String representing the object's type. Objects of the same type share the same value. |
| `reversals` | object | Yes | A list of reversals that have been applied to the transfer. |
| `reversed` | boolean | Yes | Whether the transfer has been fully reversed. If the transfer is only partially reversed, this attribute will still be false. |
| `source_transaction` | any | No | ID of the charge that was used to fund the transfer. If null, the transfer was funded from the available balance. |
| `source_type` | string | No | The source balance this transfer came from. One of `card`, `fpx`, or `bank_account`. |
| `transfer_group` | string | No | A string that identifies this transaction as part of a group. See the [Connect documentation](https://docs.stripe.com/connect/separate-charges-and-transfers#transfer-options) for details. |

## Nested Fields

### `reversals`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `data` | transfer_reversal[] | Yes | Details about each object. |
| `has_more` | boolean | Yes | True if this list has another page of items after this one that can be fetched. |
| `object` | enum: list | Yes | String representing the object's type. Objects of the same type share the same value. Always has the value `list`. |
| `url` | string | Yes | The URL where this list can be accessed. |


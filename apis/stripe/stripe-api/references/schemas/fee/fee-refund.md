# fee_refund

`Application Fee Refund` objects allow you to refund an application fee that
has previously been created but not yet refunded. Funds will be refunded to
the Stripe account from which the fee was originally collected.

Related guide: [Refunding application fees](https://docs.stripe.com/connect/destination-charges#refunding-app-fee)

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `amount` | integer | Yes | Amount, in cents (or local equivalent). |
| `balance_transaction` | any | No | Balance transaction that describes the impact on your account balance. |
| `created` | integer (unix-time) | Yes | Time at which the object was created. Measured in seconds since the Unix epoch. |
| `currency` | string (currency) | Yes | Three-letter [ISO currency code](https://www.iso.org/iso-4217-currency-codes.html), in lowercase. Must be a [supported currency](https://stripe.com/docs/currencies). |
| `fee` | any | Yes | ID of the application fee that was refunded. |
| `id` | string | Yes | Unique identifier for the object. |
| `metadata` | object | No | Set of [key-value pairs](https://docs.stripe.com/api/metadata) that you can attach to an object. This can be useful for storing additional information about the object in a structured format. |
| `object` | enum: fee_refund | Yes | String representing the object's type. Objects of the same type share the same value. |


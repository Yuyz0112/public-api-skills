# topup

To top up your Stripe balance, you create a top-up object. You can retrieve
individual top-ups, as well as list all top-ups. Top-ups are identified by a
unique, random ID.

Related guide: [Topping up your platform account](https://docs.stripe.com/connect/top-ups)

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `amount` | integer | Yes | Amount transferred. |
| `balance_transaction` | any | No | ID of the balance transaction that describes the impact of this top-up on your account balance. May not be specified depending on status of top-up. |
| `created` | integer (unix-time) | Yes | Time at which the object was created. Measured in seconds since the Unix epoch. |
| `currency` | string | Yes | Three-letter [ISO currency code](https://www.iso.org/iso-4217-currency-codes.html), in lowercase. Must be a [supported currency](https://stripe.com/docs/currencies). |
| `description` | string | No | An arbitrary string attached to the object. Often useful for displaying to users. |
| `expected_availability_date` | integer | No | Date the funds are expected to arrive in your Stripe account for payouts. This factors in delays like weekends or bank holidays. May not be specified depending on status of top-up. |
| `failure_code` | string | No | Error code explaining reason for top-up failure if available (see [the errors section](https://docs.stripe.com/api#errors) for a list of codes). |
| `failure_message` | string | No | Message to user further explaining reason for top-up failure if available. |
| `id` | string | Yes | Unique identifier for the object. |
| `livemode` | boolean | Yes | Has the value `true` if the object exists in live mode or the value `false` if the object exists in test mode. |
| `metadata` | object | Yes | Set of [key-value pairs](https://docs.stripe.com/api/metadata) that you can attach to an object. This can be useful for storing additional information about the object in a structured format. |
| `object` | enum: topup | Yes | String representing the object's type. Objects of the same type share the same value. |
| `source` | any | No | The source field is deprecated. It might not always be present in the API response. |
| `statement_descriptor` | string | No | Extra information about a top-up. This will appear on your source's bank statement. It must contain at least one letter. |
| `status` | enum: canceled, failed, pending... | Yes | The status of the top-up is either `canceled`, `failed`, `pending`, `reversed`, or `succeeded`. |
| `transfer_group` | string | No | A string that identifies this top-up as part of a group. |


# source_transaction

Some payment methods have no required amount that a customer must send.
Customers can be instructed to send any amount, and it can be made up of
multiple transactions. As such, sources can have multiple associated
transactions.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `ach_credit_transfer` | [source_transaction_ach_credit_transfer_data](source-transaction-ach-credit-transfer-data.md) | No |  |
| `amount` | integer | Yes | A positive integer in the smallest currency unit (that is, 100 cents for $1.00, or 1 for ¥1, Japanese Yen being a zero-decimal currency) representing the amount your customer has pushed to the receiver. |
| `chf_credit_transfer` | [source_transaction_chf_credit_transfer_data](source-transaction-chf-credit-transfer-data.md) | No |  |
| `created` | integer (unix-time) | Yes | Time at which the object was created. Measured in seconds since the Unix epoch. |
| `currency` | string (currency) | Yes | Three-letter [ISO currency code](https://www.iso.org/iso-4217-currency-codes.html), in lowercase. Must be a [supported currency](https://stripe.com/docs/currencies). |
| `gbp_credit_transfer` | [source_transaction_gbp_credit_transfer_data](source-transaction-gbp-credit-transfer-data.md) | No |  |
| `id` | string | Yes | Unique identifier for the object. |
| `livemode` | boolean | Yes | Has the value `true` if the object exists in live mode or the value `false` if the object exists in test mode. |
| `object` | enum: source_transaction | Yes | String representing the object's type. Objects of the same type share the same value. |
| `paper_check` | [source_transaction_paper_check_data](source-transaction-paper-check-data.md) | No |  |
| `sepa_credit_transfer` | [source_transaction_sepa_credit_transfer_data](source-transaction-sepa-credit-transfer-data.md) | No |  |
| `source` | string | Yes | The ID of the source this transaction is attached to. |
| `status` | string | Yes | The status of the transaction, one of `succeeded`, `pending`, or `failed`. |
| `type` | enum: ach_credit_transfer, ach_debit, alipay... | Yes | The type of source this transaction is attached to. |


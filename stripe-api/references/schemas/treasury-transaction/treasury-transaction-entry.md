# treasury.transaction_entry

TransactionEntries represent individual units of money movements within a single [Transaction](https://api.stripe.com#transactions).

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `balance_impact` | [treasury_transactions_resource_balance_impact](treasury-transactions-resource-balance-impact.md) | Yes |  |
| `created` | integer (unix-time) | Yes | Time at which the object was created. Measured in seconds since the Unix epoch. |
| `currency` | string (currency) | Yes | Three-letter [ISO currency code](https://www.iso.org/iso-4217-currency-codes.html), in lowercase. Must be a [supported currency](https://stripe.com/docs/currencies). |
| `effective_at` | integer (unix-time) | Yes | When the TransactionEntry will impact the FinancialAccount's balance. |
| `financial_account` | string | Yes | The FinancialAccount associated with this object. |
| `flow` | string | No | Token of the flow associated with the TransactionEntry. |
| `flow_details` | any | No | Details of the flow associated with the TransactionEntry. |
| `flow_type` | enum: credit_reversal, debit_reversal, inbound_transfer... | Yes | Type of the flow associated with the TransactionEntry. |
| `id` | string | Yes | Unique identifier for the object. |
| `livemode` | boolean | Yes | Has the value `true` if the object exists in live mode or the value `false` if the object exists in test mode. |
| `object` | enum: treasury.transaction_entry | Yes | String representing the object's type. Objects of the same type share the same value. |
| `transaction` | any | Yes | The Transaction associated with this object. |
| `type` | enum: credit_reversal, credit_reversal_posting, debit_reversal... | Yes | The specific money movement that generated the TransactionEntry. |


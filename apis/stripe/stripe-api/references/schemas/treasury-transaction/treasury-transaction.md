# treasury.transaction

Transactions represent changes to a [FinancialAccount's](https://api.stripe.com#financial_accounts) balance.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `amount` | integer | Yes | Amount (in cents) transferred. |
| `balance_impact` | [treasury_transactions_resource_balance_impact](treasury-transactions-resource-balance-impact.md) | Yes |  |
| `created` | integer (unix-time) | Yes | Time at which the object was created. Measured in seconds since the Unix epoch. |
| `currency` | string (currency) | Yes | Three-letter [ISO currency code](https://www.iso.org/iso-4217-currency-codes.html), in lowercase. Must be a [supported currency](https://stripe.com/docs/currencies). |
| `description` | string | Yes | An arbitrary string attached to the object. Often useful for displaying to users. |
| `entries` | object | No | A list of TransactionEntries that are part of this Transaction. This cannot be expanded in any list endpoints. |
| `financial_account` | string | Yes | The FinancialAccount associated with this object. |
| `flow` | string | No | ID of the flow that created the Transaction. |
| `flow_details` | any | No | Details of the flow that created the Transaction. |
| `flow_type` | enum: credit_reversal, debit_reversal, inbound_transfer... | Yes | Type of the flow that created the Transaction. |
| `id` | string | Yes | Unique identifier for the object. |
| `livemode` | boolean | Yes | Has the value `true` if the object exists in live mode or the value `false` if the object exists in test mode. |
| `object` | enum: treasury.transaction | Yes | String representing the object's type. Objects of the same type share the same value. |
| `status` | enum: open, posted, void | Yes | Status of the Transaction. |
| `status_transitions` | [treasury_transactions_resource_abstract_transaction_resource_status_transitions](treasury-transactions-resource-abstract-transaction-resource-status-transitions.md) | Yes |  |

## Nested Fields

### `entries`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `data` | treasury.transaction_entry[] | Yes | Details about each object. |
| `has_more` | boolean | Yes | True if this list has another page of items after this one that can be fetched. |
| `object` | enum: list | Yes | String representing the object's type. Objects of the same type share the same value. Always has the value `list`. |
| `url` | string | Yes | The URL where this list can be accessed. |


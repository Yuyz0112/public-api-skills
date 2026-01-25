# financial_connections.transaction

A Transaction represents a real transaction that affects a Financial Connections Account balance.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `account` | string | Yes | The ID of the Financial Connections Account this transaction belongs to. |
| `amount` | integer | Yes | The amount of this transaction, in cents (or local equivalent). |
| `currency` | string | Yes | Three-letter [ISO currency code](https://www.iso.org/iso-4217-currency-codes.html), in lowercase. Must be a [supported currency](https://stripe.com/docs/currencies). |
| `description` | string | Yes | The description of this transaction. |
| `id` | string | Yes | Unique identifier for the object. |
| `livemode` | boolean | Yes | Has the value `true` if the object exists in live mode or the value `false` if the object exists in test mode. |
| `object` | enum: financial_connections.transaction | Yes | String representing the object's type. Objects of the same type share the same value. |
| `status` | enum: pending, posted, void | Yes | The status of the transaction. |
| `status_transitions` | [bank_connections_resource_transaction_resource_status_transitions](bank-connections-resource-transaction-resource-status-transitions.md) | Yes |  |
| `transacted_at` | integer (unix-time) | Yes | Time at which the transaction was transacted. Measured in seconds since the Unix epoch. |
| `transaction_refresh` | string | Yes | The token of the transaction refresh that last updated or created this transaction. |
| `updated` | integer (unix-time) | Yes | Time at which the object was last updated. Measured in seconds since the Unix epoch. |


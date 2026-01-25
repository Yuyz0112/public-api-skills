# PlaidAccountTransaction

Descriptor for a Plaid account.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `accountCategory` | string | Yes | The category of the account (e.g., personal, business). |
| `amount` | number | Yes | The amount transacted. |
| `debitCreditMemo` | string | Yes | Memo for transaction (e.g. CREDIT) |
| `description` | string | Yes | The transaction description |
| `postedTimestamp` | string | No | The timestamp when the transaction was posted. |
| `status` | string | Yes | The status of the transaction. |
| `transactionId` | string | Yes | The identifier for the transaction. |
| `transactionTimestamp` | string | Yes | The timestamp when the transaction occurred. |


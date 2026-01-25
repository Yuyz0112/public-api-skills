# PlaidAccount

Descriptor for a Plaid account.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `accountCategory` | string | Yes | The category of the account (e.g., personal, business). |
| `accountId` | string | Yes | The Plaid account ID. |
| `accountNumberDisplay` | string | Yes | The last 2-4 digits of the account number. |
| `accountType` | string | Yes | The type of the account (e.g., checking, savings). |
| `availableBalance` | number | No | The available balance of the account. |
| `currency` | [PlaidCurrency](PlaidCurrency.md) | Yes |  |
| `currentBalance` | number | No | The current balance of the account. |
| `nickname` | string | No | The nickname of the account. |
| `productName` | string | Yes | The name of the product associated with the account. |
| `status` | string | Yes | The status of the account. |


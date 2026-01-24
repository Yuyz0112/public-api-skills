# bank_connections_resource_balance

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `as_of` | integer (unix-time) | Yes | The time that the external institution calculated this balance. Measured in seconds since the Unix epoch. |
| `cash` | [bank_connections_resource_balance_api_resource_cash_balance](bank-connections-resource-balance-api-resource-cash-balance.md) | No |  |
| `credit` | [bank_connections_resource_balance_api_resource_credit_balance](bank-connections-resource-balance-api-resource-credit-balance.md) | No |  |
| `current` | object | Yes | The balances owed to (or by) the account holder, before subtracting any outbound pending transactions or adding any inbound pending transactions.

Each key is a three-letter [ISO currency code](https://www.iso.org/iso-4217-currency-codes.html), in lowercase.

Each value is a integer amount. A positive amount indicates money owed to the account holder. A negative amount indicates money owed by the account holder. |
| `type` | enum: cash, credit | Yes | The `type` of the balance. An additional hash is included on the balance with a name matching this value. |


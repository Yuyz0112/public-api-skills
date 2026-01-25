# treasury_financial_accounts_resource_balance

Balance information for the FinancialAccount

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `cash` | object | Yes | Funds the user can spend right now. |
| `inbound_pending` | object | Yes | Funds not spendable yet, but will become available at a later time. |
| `outbound_pending` | object | Yes | Funds in the account, but not spendable because they are being held for pending outbound flows. |


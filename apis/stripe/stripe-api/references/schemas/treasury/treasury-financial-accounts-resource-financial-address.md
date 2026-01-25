# treasury_financial_accounts_resource_financial_address

FinancialAddresses contain identifying information that resolves to a FinancialAccount.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `aba` | [treasury_financial_accounts_resource_aba_record](treasury-financial-accounts-resource-aba-record.md) | No |  |
| `supported_networks` | string[] | No | The list of networks that the address supports |
| `type` | enum: aba | Yes | The type of financial address |


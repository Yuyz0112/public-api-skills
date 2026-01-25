# customer_balance_resource_cash_balance_transaction_resource_funded_transaction_resource_bank_transfer

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `eu_bank_transfer` | [customer_balance_resource_cash_balance_transaction_resource_funded_transaction_resource_bank_transfer_resource_eu_bank_transfer](customer-balance-resource-cash-balance-transaction-resource-funded-transaction-resource-bank-transfer-resource-eu-bank-transfer.md) | No |  |
| `gb_bank_transfer` | [customer_balance_resource_cash_balance_transaction_resource_funded_transaction_resource_bank_transfer_resource_gb_bank_transfer](customer-balance-resource-cash-balance-transaction-resource-funded-transaction-resource-bank-transfer-resource-gb-bank-transfer.md) | No |  |
| `jp_bank_transfer` | [customer_balance_resource_cash_balance_transaction_resource_funded_transaction_resource_bank_transfer_resource_jp_bank_transfer](customer-balance-resource-cash-balance-transaction-resource-funded-transaction-resource-bank-transfer-resource-jp-bank-transfer.md) | No |  |
| `reference` | string | No | The user-supplied reference field on the bank transfer. |
| `type` | enum: eu_bank_transfer, gb_bank_transfer, jp_bank_transfer... | Yes | The funding method type used to fund the customer balance. Permitted values include: `eu_bank_transfer`, `gb_bank_transfer`, `jp_bank_transfer`, `mx_bank_transfer`, or `us_bank_transfer`. |
| `us_bank_transfer` | [customer_balance_resource_cash_balance_transaction_resource_funded_transaction_resource_bank_transfer_resource_us_bank_transfer](customer-balance-resource-cash-balance-transaction-resource-funded-transaction-resource-bank-transfer-resource-us-bank-transfer.md) | No |  |


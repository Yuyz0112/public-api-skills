# funding_instructions_bank_transfer_financial_address

FinancialAddresses contain identifying information that resolves to a FinancialAccount.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `aba` | [funding_instructions_bank_transfer_aba_record](funding-instructions-bank-transfer-aba-record.md) | No |  |
| `iban` | [funding_instructions_bank_transfer_iban_record](funding-instructions-bank-transfer-iban-record.md) | No |  |
| `sort_code` | [funding_instructions_bank_transfer_sort_code_record](funding-instructions-bank-transfer-sort-code-record.md) | No |  |
| `spei` | [funding_instructions_bank_transfer_spei_record](funding-instructions-bank-transfer-spei-record.md) | No |  |
| `supported_networks` | string[] | No | The payment networks supported by this FinancialAddress |
| `swift` | [funding_instructions_bank_transfer_swift_record](funding-instructions-bank-transfer-swift-record.md) | No |  |
| `type` | enum: aba, iban, sort_code... | Yes | The type of financial address |
| `zengin` | [funding_instructions_bank_transfer_zengin_record](funding-instructions-bank-transfer-zengin-record.md) | No |  |


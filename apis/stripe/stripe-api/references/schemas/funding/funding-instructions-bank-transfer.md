# funding_instructions_bank_transfer

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `country` | string | Yes | The country of the bank account to fund |
| `financial_addresses` | funding_instructions_bank_transfer_financial_address[] | Yes | A list of financial addresses that can be used to fund a particular balance |
| `type` | enum: eu_bank_transfer, jp_bank_transfer | Yes | The bank_transfer type |


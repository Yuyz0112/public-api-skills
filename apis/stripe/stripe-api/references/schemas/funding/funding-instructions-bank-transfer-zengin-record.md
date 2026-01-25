# funding_instructions_bank_transfer_zengin_record

Zengin Records contain Japan bank account details per the Zengin format.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `account_holder_address` | [address](address.md) | Yes |  |
| `account_holder_name` | string | No | The account holder name |
| `account_number` | string | No | The account number |
| `account_type` | string | No | The bank account type. In Japan, this can only be `futsu` or `toza`. |
| `bank_address` | [address](address.md) | Yes |  |
| `bank_code` | string | No | The bank code of the account |
| `bank_name` | string | No | The bank name of the account |
| `branch_code` | string | No | The branch code of the account |
| `branch_name` | string | No | The branch name of the account |


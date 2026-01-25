# funding_instructions_bank_transfer_sort_code_record

Sort Code Records contain U.K. bank account details per the sort code format.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `account_holder_address` | [address](address.md) | Yes |  |
| `account_holder_name` | string | Yes | The name of the person or business that owns the bank account |
| `account_number` | string | Yes | The account number |
| `bank_address` | [address](address.md) | Yes |  |
| `sort_code` | string | Yes | The six-digit sort code |


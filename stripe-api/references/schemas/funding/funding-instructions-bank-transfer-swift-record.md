# funding_instructions_bank_transfer_swift_record

SWIFT Records contain U.S. bank account details per the SWIFT format.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `account_holder_address` | [address](address.md) | Yes |  |
| `account_holder_name` | string | Yes | The account holder name |
| `account_number` | string | Yes | The account number |
| `account_type` | string | Yes | The account type |
| `bank_address` | [address](address.md) | Yes |  |
| `bank_name` | string | Yes | The bank name |
| `swift_code` | string | Yes | The SWIFT code |


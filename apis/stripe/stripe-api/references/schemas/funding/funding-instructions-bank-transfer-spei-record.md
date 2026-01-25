# funding_instructions_bank_transfer_spei_record

SPEI Records contain Mexico bank account details per the SPEI format.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `account_holder_address` | [address](address.md) | Yes |  |
| `account_holder_name` | string | Yes | The account holder name |
| `bank_address` | [address](address.md) | Yes |  |
| `bank_code` | string | Yes | The three-digit bank code |
| `bank_name` | string | Yes | The short banking institution name |
| `clabe` | string | Yes | The CLABE number |


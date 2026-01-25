# treasury_financial_accounts_resource_aba_record

ABA Records contain U.S. bank account details per the ABA format.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `account_holder_name` | string | Yes | The name of the person or business that owns the bank account. |
| `account_number` | string | No | The account number. |
| `account_number_last4` | string | Yes | The last four characters of the account number. |
| `bank_name` | string | Yes | Name of the bank. |
| `routing_number` | string | Yes | Routing number for the account. |


# payment_method_nz_bank_account

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `account_holder_name` | string | No | The name on the bank account. Only present if the account holder name is different from the name of the authorized signatory collected in the PaymentMethod’s billing details. |
| `bank_code` | string | Yes | The numeric code for the bank account's bank. |
| `bank_name` | string | Yes | The name of the bank. |
| `branch_code` | string | Yes | The numeric code for the bank account's bank branch. |
| `last4` | string | Yes | Last four digits of the bank account number. |
| `suffix` | string | No | The suffix of the bank account number. |


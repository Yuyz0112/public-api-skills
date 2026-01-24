# bank_connections_resource_account_number_details

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `expected_expiry_date` | integer (unix-time) | No | When the account number is expected to expire, if applicable. |
| `identifier_type` | enum: account_number, tokenized_account_number | Yes | The type of account number associated with the account. |
| `status` | enum: deactivated, transactable | Yes | Whether the account number is currently active and usable for transactions. |
| `supported_networks` | string[] | Yes | The payment networks that the account number can be used for. |


# payment_method_details_ach_debit

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `account_holder_type` | enum: company, individual | No | Type of entity that holds the account. This can be either `individual` or `company`. |
| `bank_name` | string | No | Name of the bank associated with the bank account. |
| `country` | string | No | Two-letter ISO code representing the country the bank account is located in. |
| `fingerprint` | string | No | Uniquely identifies this particular bank account. You can use this attribute to check whether two bank accounts are the same. |
| `last4` | string | No | Last four digits of the bank account number. |
| `routing_number` | string | No | Routing transit number of the bank account. |


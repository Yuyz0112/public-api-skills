# payment_method_details_payment_record_us_bank_account

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `account_holder_type` | enum: company, individual | No | The type of entity that holds the account. This can be either 'individual' or 'company'. |
| `account_type` | enum: checking, savings | No | The type of the bank account. This can be either 'checking' or 'savings'. |
| `bank_name` | string | No | Name of the bank associated with the bank account. |
| `expected_debit_date` | string | No | Estimated date to debit the customer's bank account. A date string in YYYY-MM-DD format. |
| `fingerprint` | string | No | Uniquely identifies this particular bank account. You can use this attribute to check whether two bank accounts are the same. |
| `last4` | string | No | Last four digits of the bank account number. |
| `mandate` | any | No | ID of the mandate used to make this payment. |
| `payment_reference` | string | No | The ACH payment reference for this transaction. |
| `routing_number` | string | No | The routing number for the bank account. |


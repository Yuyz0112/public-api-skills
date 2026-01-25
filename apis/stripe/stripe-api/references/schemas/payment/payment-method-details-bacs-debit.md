# payment_method_details_bacs_debit

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `expected_debit_date` | string | No | Estimated date to debit the customer's bank account. A date string in YYYY-MM-DD format. |
| `fingerprint` | string | No | Uniquely identifies this particular bank account. You can use this attribute to check whether two bank accounts are the same. |
| `last4` | string | No | Last four digits of the bank account number. |
| `mandate` | string | No | ID of the mandate used to make this payment. |
| `sort_code` | string | No | Sort code of the bank account. (e.g., `10-20-30`) |


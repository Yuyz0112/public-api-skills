# payment_method_details_acss_debit

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `bank_name` | string | No | Name of the bank associated with the bank account. |
| `expected_debit_date` | string | No | Estimated date to debit the customer's bank account. A date string in YYYY-MM-DD format. |
| `fingerprint` | string | No | Uniquely identifies this particular bank account. You can use this attribute to check whether two bank accounts are the same. |
| `institution_number` | string | No | Institution number of the bank account |
| `last4` | string | No | Last four digits of the bank account number. |
| `mandate` | string | No | ID of the mandate used to make this payment. |
| `transit_number` | string | No | Transit number of the bank account. |


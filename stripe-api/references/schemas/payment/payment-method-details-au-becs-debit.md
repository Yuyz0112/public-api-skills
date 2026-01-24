# payment_method_details_au_becs_debit

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `bsb_number` | string | No | Bank-State-Branch number of the bank account. |
| `expected_debit_date` | string | No | Estimated date to debit the customer's bank account. A date string in YYYY-MM-DD format. |
| `fingerprint` | string | No | Uniquely identifies this particular bank account. You can use this attribute to check whether two bank accounts are the same. |
| `last4` | string | No | Last four digits of the bank account number. |
| `mandate` | string | No | ID of the mandate used to make this payment. |


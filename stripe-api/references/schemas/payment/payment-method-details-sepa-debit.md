# payment_method_details_sepa_debit

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `bank_code` | string | No | Bank code of bank associated with the bank account. |
| `branch_code` | string | No | Branch code of bank associated with the bank account. |
| `country` | string | No | Two-letter ISO code representing the country the bank account is located in. |
| `expected_debit_date` | string | No | Estimated date to debit the customer's bank account. A date string in YYYY-MM-DD format. |
| `fingerprint` | string | No | Uniquely identifies this particular bank account. You can use this attribute to check whether two bank accounts are the same. |
| `last4` | string | No | Last four characters of the IBAN. |
| `mandate` | string | No | Find the ID of the mandate used for this payment under the [payment_method_details.sepa_debit.mandate](https://docs.stripe.com/api/charges/object#charge_object-payment_method_details-sepa_debit-mandate) property on the Charge. Use this mandate ID to [retrieve the Mandate](https://docs.stripe.com/api/mandates/retrieve). |


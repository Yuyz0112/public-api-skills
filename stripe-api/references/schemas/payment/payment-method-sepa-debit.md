# payment_method_sepa_debit

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `bank_code` | string | No | Bank code of bank associated with the bank account. |
| `branch_code` | string | No | Branch code of bank associated with the bank account. |
| `country` | string | No | Two-letter ISO code representing the country the bank account is located in. |
| `fingerprint` | string | No | Uniquely identifies this particular bank account. You can use this attribute to check whether two bank accounts are the same. |
| `generated_from` | any | No | Information about the object that generated this PaymentMethod. |
| `last4` | string | No | Last four characters of the IBAN. |


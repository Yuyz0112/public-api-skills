# funding_instructions_bank_transfer_iban_record

Iban Records contain E.U. bank account details per the SEPA format.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `account_holder_address` | [address](address.md) | Yes |  |
| `account_holder_name` | string | Yes | The name of the person or business that owns the bank account |
| `bank_address` | [address](address.md) | Yes |  |
| `bic` | string | Yes | The BIC/SWIFT code of the account. |
| `country` | string | Yes | Two-letter country code ([ISO 3166-1 alpha-2](https://en.wikipedia.org/wiki/ISO_3166-1_alpha-2)). |
| `iban` | string | Yes | The IBAN of the account. |


# payment_method_options_customer_balance_bank_transfer

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `eu_bank_transfer` | [payment_method_options_customer_balance_eu_bank_account](payment-method-options-customer-balance-eu-bank-account.md) | No |  |
| `requested_address_types` | string[] | No | List of address types that should be returned in the financial_addresses response. If not specified, all valid types will be returned.

Permitted values include: `sort_code`, `zengin`, `iban`, or `spei`. |
| `type` | enum: eu_bank_transfer, gb_bank_transfer, jp_bank_transfer... | No | The bank transfer type that this PaymentIntent is allowed to use for funding Permitted values include: `eu_bank_transfer`, `gb_bank_transfer`, `jp_bank_transfer`, `mx_bank_transfer`, or `us_bank_transfer`. |


# payment_intent_next_action_display_bank_transfer_instructions

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `amount_remaining` | integer | No | The remaining amount that needs to be transferred to complete the payment. |
| `currency` | string (currency) | No | Three-letter [ISO currency code](https://www.iso.org/iso-4217-currency-codes.html), in lowercase. Must be a [supported currency](https://stripe.com/docs/currencies). |
| `financial_addresses` | funding_instructions_bank_transfer_financial_address[] | No | A list of financial addresses that can be used to fund the customer balance |
| `hosted_instructions_url` | string | No | A link to a hosted page that guides your customer through completing the transfer. |
| `reference` | string | No | A string identifying this payment. Instruct your customer to include this code in the reference or memo field of their bank transfer. |
| `type` | enum: eu_bank_transfer, gb_bank_transfer, jp_bank_transfer... | Yes | Type of bank transfer |


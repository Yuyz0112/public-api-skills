# payment_method_card_wallet

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `amex_express_checkout` | [payment_method_card_wallet_amex_express_checkout](payment-method-card-wallet-amex-express-checkout.md) | No |  |
| `apple_pay` | [payment_method_card_wallet_apple_pay](payment-method-card-wallet-apple-pay.md) | No |  |
| `dynamic_last4` | string | No | (For tokenized numbers only.) The last four digits of the device account number. |
| `google_pay` | [payment_method_card_wallet_google_pay](payment-method-card-wallet-google-pay.md) | No |  |
| `link` | [payment_method_card_wallet_link](payment-method-card-wallet-link.md) | No |  |
| `masterpass` | [payment_method_card_wallet_masterpass](payment-method-card-wallet-masterpass.md) | No |  |
| `samsung_pay` | [payment_method_card_wallet_samsung_pay](payment-method-card-wallet-samsung-pay.md) | No |  |
| `type` | enum: amex_express_checkout, apple_pay, google_pay... | Yes | The type of the card wallet, one of `amex_express_checkout`, `apple_pay`, `google_pay`, `masterpass`, `samsung_pay`, `visa_checkout`, or `link`. An additional hash is included on the Wallet subhash with a name matching this value. It contains additional information specific to the card wallet type. |
| `visa_checkout` | [payment_method_card_wallet_visa_checkout](payment-method-card-wallet-visa-checkout.md) | No |  |


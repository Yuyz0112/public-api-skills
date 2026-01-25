# setup_attempt_payment_method_details_card_wallet

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `apple_pay` | [payment_method_details_card_wallet_apple_pay](payment-method-details-card-wallet-apple-pay.md) | No |  |
| `google_pay` | [payment_method_details_card_wallet_google_pay](payment-method-details-card-wallet-google-pay.md) | No |  |
| `type` | enum: apple_pay, google_pay, link | Yes | The type of the card wallet, one of `apple_pay`, `google_pay`, or `link`. An additional hash is included on the Wallet subhash with a name matching this value. It contains additional information specific to the card wallet type. |


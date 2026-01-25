# payments_primitives_payment_records_resource_payment_method_card_details_resource_wallet

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `apple_pay` | [payments_primitives_payment_records_resource_payment_method_card_details_resource_wallet_resource_apple_pay](payments-primitives-payment-records-resource-payment-method-card-details-resource-wallet-resource-apple-pay.md) | No |  |
| `dynamic_last4` | string | No | (For tokenized numbers only.) The last four digits of the device account number. |
| `google_pay` | [payments_primitives_payment_records_resource_payment_method_card_details_resource_wallet_resource_google_pay](payments-primitives-payment-records-resource-payment-method-card-details-resource-wallet-resource-google-pay.md) | No |  |
| `type` | string | Yes | The type of the card wallet, one of `apple_pay` or `google_pay`. An additional hash is included on the Wallet subhash with a name matching this value. It contains additional information specific to the card wallet type. |


# payment_method_options_card_present

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `capture_method` | enum: manual, manual_preferred | No | Controls when the funds will be captured from the customer's account. |
| `request_extended_authorization` | boolean | No | Request ability to capture this payment beyond the standard [authorization validity window](https://docs.stripe.com/terminal/features/extended-authorizations#authorization-validity) |
| `request_incremental_authorization_support` | boolean | No | Request ability to [increment](https://docs.stripe.com/terminal/features/incremental-authorizations) this PaymentIntent if the combination of MCC and card brand is eligible. Check [incremental_authorization_supported](https://docs.stripe.com/api/charges/object#charge_object-payment_method_details-card_present-incremental_authorization_supported) in the [Confirm](https://docs.stripe.com/api/payment_intents/confirm) response to verify support. |
| `routing` | [payment_method_options_card_present_routing](payment-method-options-card-present-routing.md) | No |  |


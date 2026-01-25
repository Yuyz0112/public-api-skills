# payment_intent_next_action

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `alipay_handle_redirect` | [payment_intent_next_action_alipay_handle_redirect](payment-intent-next-action-alipay-handle-redirect.md) | No |  |
| `boleto_display_details` | [payment_intent_next_action_boleto](payment-intent-next-action-boleto.md) | No |  |
| `card_await_notification` | [payment_intent_next_action_card_await_notification](payment-intent-next-action-card-await-notification.md) | No |  |
| `cashapp_handle_redirect_or_display_qr_code` | [payment_intent_next_action_cashapp_handle_redirect_or_display_qr_code](payment-intent-next-action-cashapp-handle-redirect-or-display-qr-code.md) | No |  |
| `display_bank_transfer_instructions` | [payment_intent_next_action_display_bank_transfer_instructions](payment-intent-next-action-display-bank-transfer-instructions.md) | No |  |
| `konbini_display_details` | [payment_intent_next_action_konbini](payment-intent-next-action-konbini.md) | No |  |
| `multibanco_display_details` | [payment_intent_next_action_display_multibanco_details](payment-intent-next-action-display-multibanco-details.md) | No |  |
| `oxxo_display_details` | [payment_intent_next_action_display_oxxo_details](payment-intent-next-action-display-oxxo-details.md) | No |  |
| `paynow_display_qr_code` | [payment_intent_next_action_paynow_display_qr_code](payment-intent-next-action-paynow-display-qr-code.md) | No |  |
| `pix_display_qr_code` | [payment_intent_next_action_pix_display_qr_code](payment-intent-next-action-pix-display-qr-code.md) | No |  |
| `promptpay_display_qr_code` | [payment_intent_next_action_promptpay_display_qr_code](payment-intent-next-action-promptpay-display-qr-code.md) | No |  |
| `redirect_to_url` | [payment_intent_next_action_redirect_to_url](payment-intent-next-action-redirect-to-url.md) | No |  |
| `swish_handle_redirect_or_display_qr_code` | [payment_intent_next_action_swish_handle_redirect_or_display_qr_code](payment-intent-next-action-swish-handle-redirect-or-display-qr-code.md) | No |  |
| `type` | string | Yes | Type of the next action to perform. Refer to the other child attributes under `next_action` for available values. Examples include: `redirect_to_url`, `use_stripe_sdk`, `alipay_handle_redirect`, `oxxo_display_details`, or `verify_with_microdeposits`. |
| `use_stripe_sdk` | object | No | When confirming a PaymentIntent with Stripe.js, Stripe.js depends on the contents of this dictionary to invoke authentication flows. The shape of the contents is subject to change and is only intended to be used by Stripe.js. |
| `verify_with_microdeposits` | [payment_intent_next_action_verify_with_microdeposits](payment-intent-next-action-verify-with-microdeposits.md) | No |  |
| `wechat_pay_display_qr_code` | [payment_intent_next_action_wechat_pay_display_qr_code](payment-intent-next-action-wechat-pay-display-qr-code.md) | No |  |
| `wechat_pay_redirect_to_android_app` | [payment_intent_next_action_wechat_pay_redirect_to_android_app](payment-intent-next-action-wechat-pay-redirect-to-android-app.md) | No |  |
| `wechat_pay_redirect_to_ios_app` | [payment_intent_next_action_wechat_pay_redirect_to_ios_app](payment-intent-next-action-wechat-pay-redirect-to-ios-app.md) | No |  |


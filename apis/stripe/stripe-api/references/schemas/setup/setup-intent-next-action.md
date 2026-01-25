# setup_intent_next_action

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `cashapp_handle_redirect_or_display_qr_code` | [payment_intent_next_action_cashapp_handle_redirect_or_display_qr_code](payment-intent-next-action-cashapp-handle-redirect-or-display-qr-code.md) | No |  |
| `redirect_to_url` | [setup_intent_next_action_redirect_to_url](setup-intent-next-action-redirect-to-url.md) | No |  |
| `type` | string | Yes | Type of the next action to perform. Refer to the other child attributes under `next_action` for available values. Examples include: `redirect_to_url`, `use_stripe_sdk`, `alipay_handle_redirect`, `oxxo_display_details`, or `verify_with_microdeposits`. |
| `use_stripe_sdk` | object | No | When confirming a SetupIntent with Stripe.js, Stripe.js depends on the contents of this dictionary to invoke authentication flows. The shape of the contents is subject to change and is only intended to be used by Stripe.js. |
| `verify_with_microdeposits` | [setup_intent_next_action_verify_with_microdeposits](setup-intent-next-action-verify-with-microdeposits.md) | No |  |


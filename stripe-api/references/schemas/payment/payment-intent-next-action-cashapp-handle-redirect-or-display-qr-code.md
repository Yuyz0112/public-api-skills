# payment_intent_next_action_cashapp_handle_redirect_or_display_qr_code

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `hosted_instructions_url` | string | Yes | The URL to the hosted Cash App Pay instructions page, which allows customers to view the QR code, and supports QR code refreshing on expiration. |
| `mobile_auth_url` | string | Yes | The url for mobile redirect based auth |
| `qr_code` | [payment_intent_next_action_cashapp_qr_code](payment-intent-next-action-cashapp-qr-code.md) | Yes |  |


# payment_intent_next_action_wechat_pay_redirect_to_android_app

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `app_id` | string | Yes | app_id is the APP ID registered on WeChat open platform |
| `nonce_str` | string | Yes | nonce_str is a random string |
| `package` | string | Yes | package is static value |
| `partner_id` | string | Yes | an unique merchant ID assigned by WeChat Pay |
| `prepay_id` | string | Yes | an unique trading ID assigned by WeChat Pay |
| `sign` | string | Yes | A signature |
| `timestamp` | string | Yes | Specifies the current time in epoch format |


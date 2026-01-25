# payment_intent_next_action_alipay_handle_redirect

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `native_data` | string | No | The native data to be used with Alipay SDK you must redirect your customer to in order to authenticate the payment in an Android App. |
| `native_url` | string | No | The native URL you must redirect your customer to in order to authenticate the payment in an iOS App. |
| `return_url` | string | No | If the customer does not exit their browser while authenticating, they will be redirected to this specified URL after completion. |
| `url` | string | No | The URL you must redirect your customer to in order to authenticate the payment. |


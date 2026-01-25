# payment_intent_next_action_card_await_notification

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `charge_attempt_at` | integer (unix-time) | No | The time that payment will be attempted. If customer approval is required, they need to provide approval before this time. |
| `customer_approval_required` | boolean | No | For payments greater than INR 15000, the customer must provide explicit approval of the payment with their bank. For payments of lower amount, no customer action is required. |


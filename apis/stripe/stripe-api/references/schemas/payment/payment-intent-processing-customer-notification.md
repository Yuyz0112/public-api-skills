# payment_intent_processing_customer_notification

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `approval_requested` | boolean | No | Whether customer approval has been requested for this payment. For payments greater than INR 15000 or mandate amount, the customer must provide explicit approval of the payment with their bank. |
| `completes_at` | integer (unix-time) | No | If customer approval is required, they need to provide approval before this time. |


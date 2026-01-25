# payment_method_details_card_present_offline

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `stored_at` | integer (unix-time) | No | Time at which the payment was collected while offline |
| `type` | enum: deferred | No | The method used to process this payment method offline. Only deferred is allowed. |


# subscriptions_trials_resource_end_behavior

Defines how a subscription behaves when a free trial ends.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `missing_payment_method` | enum: cancel, create_invoice, pause | Yes | Indicates how the subscription should change when the trial ends if the user did not provide a payment method. |


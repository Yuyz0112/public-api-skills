# portal_subscription_cancel

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `cancellation_reason` | [portal_subscription_cancellation_reason](portal-subscription-cancellation-reason.md) | Yes |  |
| `enabled` | boolean | Yes | Whether the feature is enabled. |
| `mode` | enum: at_period_end, immediately | Yes | Whether to cancel subscriptions immediately or at the end of the billing period. |
| `proration_behavior` | enum: always_invoice, create_prorations, none | Yes | Whether to create prorations when canceling subscriptions. Possible values are `none` and `create_prorations`. |


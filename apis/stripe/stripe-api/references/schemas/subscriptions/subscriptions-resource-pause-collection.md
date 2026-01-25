# subscriptions_resource_pause_collection

The Pause Collection settings determine how we will pause collection for this subscription and for how long the subscription
should be paused.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `behavior` | enum: keep_as_draft, mark_uncollectible, void | Yes | The payment collection behavior for this subscription while paused. One of `keep_as_draft`, `mark_uncollectible`, or `void`. |
| `resumes_at` | integer (unix-time) | No | The time after which the subscription will resume collecting payments. |


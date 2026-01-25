# payment_links_resource_completed_sessions

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `count` | integer | Yes | The current number of checkout sessions that have been completed on the payment link which count towards the `completed_sessions` restriction to be met. |
| `limit` | integer | Yes | The maximum number of checkout sessions that can be completed for the `completed_sessions` restriction to be met. |


# hook-delivery-item

Delivery made by a webhook, without request and response information.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | integer (int64) | Yes | Unique identifier of the webhook delivery. |
| `guid` | string | Yes | Unique identifier for the event (shared with all deliveries for all webhooks that subscribe to this event). |
| `delivered_at` | string (date-time) | Yes | Time when the webhook delivery occurred. |
| `redelivery` | boolean | Yes | Whether the webhook delivery is a redelivery. |
| `duration` | number | Yes | Time spent delivering. |
| `status` | string | Yes | Describes the response returned after attempting the delivery. |
| `status_code` | integer | Yes | Status code received when delivery was made. |
| `event` | string | Yes | The event that triggered the delivery. |
| `action` | string | Yes | The type of activity for the event that triggered the delivery. |
| `installation_id` | integer (int64) | Yes | The id of the GitHub App installation associated with this event. |
| `repository_id` | integer (int64) | Yes | The id of the repository associated with this event. |
| `throttled_at` | string (date-time) | No | Time when the webhook delivery was throttled. |


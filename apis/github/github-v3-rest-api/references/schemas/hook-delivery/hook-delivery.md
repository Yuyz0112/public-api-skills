# hook-delivery

Delivery made by a webhook.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | integer | Yes | Unique identifier of the delivery. |
| `guid` | string | Yes | Unique identifier for the event (shared with all deliveries for all webhooks that subscribe to this event). |
| `delivered_at` | string (date-time) | Yes | Time when the delivery was delivered. |
| `redelivery` | boolean | Yes | Whether the delivery is a redelivery. |
| `duration` | number | Yes | Time spent delivering. |
| `status` | string | Yes | Description of the status of the attempted delivery |
| `status_code` | integer | Yes | Status code received when delivery was made. |
| `event` | string | Yes | The event that triggered the delivery. |
| `action` | string | Yes | The type of activity for the event that triggered the delivery. |
| `installation_id` | integer | Yes | The id of the GitHub App installation associated with this event. |
| `repository_id` | integer | Yes | The id of the repository associated with this event. |
| `throttled_at` | string (date-time) | No | Time when the webhook delivery was throttled. |
| `url` | string | No | The URL target of the delivery. |
| `request` | object | Yes |  |
| `response` | object | Yes |  |

## Nested Fields

### `request`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `headers` | object | Yes | The request headers sent with the webhook delivery. |
| `payload` | object | Yes | The webhook payload. |

### `response`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `headers` | object | Yes | The response headers received when the delivery was made. |
| `payload` | string | Yes | The response payload received. |


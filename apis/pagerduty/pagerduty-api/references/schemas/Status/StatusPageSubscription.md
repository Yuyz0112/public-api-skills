# StatusPageSubscription

A StatusPageSubscription resource represents a subscription to a specific status page entity.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `channel` | enum: webhook, email, slack | No | The channel of the subscription. |
| `contact` | string | No | The subscriber's contact - email address, webhook URL, etc... |
| `id` | string | No | The ID of the Subscription. |
| `self` | string | No | The path in which the Subscription resource is accessible. |
| `status` | enum: active, pending, suspended | No | The status of the Subscription. |
| `status_page` | object | No | Status Page |
| `subscribable_object` | object | No | The subscribed entity for a given subscription. |
| `type` | string | No | A string that determines the schema of the object. |

## Nested Fields

### `status_page`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | string | Yes | Status page unique identifier |
| `type` | string | No | A string that determines the schema of the object. |

### `subscribable_object`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | string | No | The ID of the subscribed entity. |
| `type` | enum: status_page, status_page_service, status_page_post | No | The type of the subscribed entity. |


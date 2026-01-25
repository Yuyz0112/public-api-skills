# ActivitySubscriptionCreateResponse

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `data` | object | No |  |
| `errors` | Problem[] | No |  |
| `meta` | object | No |  |

## Nested Fields

### `data`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `subscription` | [ActivitySubscription](ActivitySubscription.md) | No |  |
| `total_subscriptions_for_instance_id` | integer | No |  |

### `meta`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `total_subscriptions` | integer (int32) | No | Number of active subscriptions. |


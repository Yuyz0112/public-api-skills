# ActivitySubscriptionDeleteResponse

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
| `deleted` | boolean | No |  |

### `meta`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `total_subscriptions` | integer (int32) | No | Number of active subscriptions remaining. |


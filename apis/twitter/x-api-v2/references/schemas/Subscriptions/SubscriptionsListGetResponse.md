# SubscriptionsListGetResponse

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `data` | object | No | The list of active subscriptions for a specified webhook |
| `errors` | Problem[] | No |  |

## Nested Fields

### `data`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `application_id` | string | Yes | The application ID |
| `subscriptions` | object[] | Yes | List of active subscriptions for the webhook |
| `webhook_id` | string | Yes | The associated webhook ID |
| `webhook_url` | string | Yes | The url for the associated webhook |

#### `data.subscriptions`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `user_id` | string | No | The ID of the user the webhook is subscribed to |


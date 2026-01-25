# SubscriptionsCountGetResponse

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `data` | object | No | The count of active subscriptions across all webhooks |
| `errors` | Problem[] | No |  |

## Nested Fields

### `data`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `account_name` | string | Yes | The account name |
| `provisioned_count` | string | Yes | The limit for subscriptions for this app |
| `subscriptions_count_all` | string | Yes | The number of active subscriptions across all webhooks |
| `subscriptions_count_direct_messages` | string | Yes | The number of active direct message subscriptions |


# WebhookSubscriptionUpdate

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `webhook_subscription` | object | No |  |

## Nested Fields

### `webhook_subscription`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `description` | string | No | A short description of the webhook subscription. |
| `events` | string[] | No | The set of outbound event types the subscription will receive. |
| `filter` | object | No |  |
| `active` | boolean | No | If true, a webhook will be sent. True is the default state. If false, a webhook will not be sent. |
| `oauth_client_id` | string | No | The ID of the OAuth client to use for authenticating webhook requests. Optional field. |

#### `webhook_subscription.filter`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | string | No | The id of the object being used as the filter.  This field is required for all filter types except account_reference. |
| `type` | enum: account_reference, service_reference, team_reference | No | The type of object being used as the filter. |


# WebhookLinksGetResponse

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `data` | object | No | The list of active webhook links for a given stream |
| `errors` | Problem[] | No |  |

## Nested Fields

### `data`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `links` | object[] | Yes | list of links |

#### `data.links`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `application_id` | string | No | The application ID |
| `business_user_id` | string | No | The user ID |
| `created_at` | string (data-time) | No | The datetime the webhook was linked to the stream |
| `fields` | string[] | No | Requested fields to be rendered |
| `instance_id` | string | No | The stream ID associated with the FilteredStream instance |
| `webhook_id` | string | No | The unique identifier for the webhook |


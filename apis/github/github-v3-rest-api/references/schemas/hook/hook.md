# hook

Webhooks for repositories.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `type` | string | Yes |  |
| `id` | integer | Yes | Unique identifier of the webhook. |
| `name` | string | Yes | The name of a valid service, use 'web' for a webhook. |
| `active` | boolean | Yes | Determines whether the hook is actually triggered on pushes. |
| `events` | string[] | Yes | Determines what events the hook is triggered for. Default: ['push']. |
| `config` | [webhook-config](webhook-config.md) | Yes |  |
| `updated_at` | string (date-time) | Yes |  |
| `created_at` | string (date-time) | Yes |  |
| `url` | string (uri) | Yes |  |
| `test_url` | string (uri) | Yes |  |
| `ping_url` | string (uri) | Yes |  |
| `deliveries_url` | string (uri) | No |  |
| `last_response` | [hook-response](hook-response.md) | Yes |  |


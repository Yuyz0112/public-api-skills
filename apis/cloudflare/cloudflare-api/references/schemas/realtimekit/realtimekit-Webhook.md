# realtimekit_Webhook

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `created_at` | string (date-time) | Yes | Timestamp when this webhook was created |
| `enabled` | boolean | Yes | Set to true if the webhook is active |
| `events` | string[] | Yes | Events this webhook will send updates for |
| `id` | string (uuid) | Yes | ID of the webhook |
| `name` | string | Yes | Name of the webhook |
| `updated_at` | string (date-time) | Yes | Timestamp when this webhook was updated |
| `url` | string (uri) | Yes | URL the webhook will send events to |


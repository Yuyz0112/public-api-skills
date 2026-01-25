# realtimekit_WebhookRequest

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `enabled` | boolean | No | Set whether or not the webhook should be active when created |
| `events` | string[] | Yes | Events that this webhook will get triggered by |
| `name` | string | Yes | Name of the webhook |
| `url` | string (uri) | Yes | URL this webhook will send events to |


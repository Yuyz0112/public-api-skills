# mq_event-subscription

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `created_at` | string (date-time) | Yes | When the subscription was created |
| `destination` | [mq_event-destination](mq-event-destination.md) | Yes |  |
| `enabled` | boolean | Yes | Whether the subscription is active |
| `events` | string[] | Yes | List of event types this subscription handles |
| `id` | string | Yes | Unique identifier for the subscription |
| `modified_at` | string (date-time) | Yes | When the subscription was last modified |
| `name` | string | Yes | Name of the subscription |
| `source` | [mq_event-source](mq-event-source.md) | Yes |  |


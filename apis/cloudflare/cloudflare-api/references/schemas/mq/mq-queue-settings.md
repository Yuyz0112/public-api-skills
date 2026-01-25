# mq_queue-settings

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `delivery_delay` | number | No | Number of seconds to delay delivery of all messages to consumers. |
| `delivery_paused` | boolean | No | Indicates if message delivery to consumers is currently paused. |
| `message_retention_period` | number | No | Number of seconds after which an unconsumed message will be delayed. |


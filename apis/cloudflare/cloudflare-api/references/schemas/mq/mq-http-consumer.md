# mq_http-consumer

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `consumer_id` | [mq_identifier](mq-identifier.md) | No |  |
| `created_on` | string | No |  |
| `queue_id` | [mq_identifier](mq-identifier.md) | No |  |
| `settings` | object | No |  |
| `type` | enum: http_pull | No |  |

## Nested Fields

### `settings`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `batch_size` | [mq_batch-size](mq-batch-size.md) | No |  |
| `max_retries` | [mq_max-retries](mq-max-retries.md) | No |  |
| `retry_delay` | [mq_retry-delay](mq-retry-delay.md) | No |  |
| `visibility_timeout_ms` | [mq_visibility-timeout](mq-visibility-timeout.md) | No |  |


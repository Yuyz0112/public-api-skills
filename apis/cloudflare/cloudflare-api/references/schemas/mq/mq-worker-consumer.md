# mq_worker-consumer

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `consumer_id` | [mq_identifier](mq-identifier.md) | No |  |
| `created_on` | string | No |  |
| `queue_id` | [mq_identifier](mq-identifier.md) | No |  |
| `script` | object | No |  |
| `script_name` | object | No |  |
| `settings` | object | No |  |
| `type` | enum: worker | No |  |

## Nested Fields

### `settings`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `batch_size` | [mq_batch-size](mq-batch-size.md) | No |  |
| `max_concurrency` | [mq_max-concurrency](mq-max-concurrency.md) | No |  |
| `max_retries` | [mq_max-retries](mq-max-retries.md) | No |  |
| `max_wait_time_ms` | [mq_max-wait-time](mq-max-wait-time.md) | No |  |
| `retry_delay` | [mq_retry-delay](mq-retry-delay.md) | No |  |


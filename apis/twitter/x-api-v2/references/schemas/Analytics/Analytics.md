# Analytics

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `data` | object[] | No |  |
| `errors` | Problem[] | No |  |

## Nested Fields

### `data`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | [TweetId](TweetId.md) | No |  |
| `timestamped_metrics` | TimestampedMetrics[] | No | Array containing metrics data along with the timestamps of their recording. |


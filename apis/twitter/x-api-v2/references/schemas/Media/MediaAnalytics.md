# MediaAnalytics

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
| `media_key` | [MediaKey](MediaKey.md) | No |  |
| `timestamped_metrics` | MediaTimestampedMetrics[] | No | Array containing metrics data along with the timestamps of their recording. |


# dns-analytics_result

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `data` | [dns-analytics_data](dns-analytics-data.md) | Yes |  |
| `data_lag` | number | Yes | Number of seconds between current time and last processed event, in another words how many seconds of data could be missing. |
| `max` | object | Yes | Maximum results for each metric (object mapping metric names to values). Currently always an empty object. |
| `min` | object | Yes | Minimum results for each metric (object mapping metric names to values). Currently always an empty object. |
| `query` | [dns-analytics_query](dns-analytics-query.md) | Yes |  |
| `rows` | number | Yes | Total number of rows in the result. |
| `totals` | object | Yes | Total results for metrics across all data (object mapping metric names to values). |


# dns-analytics_query

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `dimensions` | string[] | Yes | Array of dimension names. |
| `filters` | [dns-analytics_filters](dns-analytics-filters.md) | No |  |
| `limit` | [dns-analytics_limit](dns-analytics-limit.md) | Yes |  |
| `metrics` | string[] | Yes | Array of metric names. |
| `since` | [dns-analytics_since](dns-analytics-since.md) | Yes |  |
| `sort` | string[] | No | Array of dimensions to sort by, where each dimension may be prefixed by - (descending) or + (ascending). |
| `until` | [dns-analytics_until](dns-analytics-until.md) | Yes |  |


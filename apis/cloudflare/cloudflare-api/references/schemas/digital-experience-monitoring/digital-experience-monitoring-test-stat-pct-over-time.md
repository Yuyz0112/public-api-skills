# digital-experience-monitoring_test_stat_pct_over_time

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `avg` | number (float) | No | average observed in the time period |
| `max` | number (float) | No | highest observed in the time period |
| `min` | number (float) | No | lowest  observed in the time period |
| `slots` | object[] | Yes |  |

## Nested Fields

### `slots`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `timestamp` | string | Yes |  |
| `value` | number (float) | Yes |  |


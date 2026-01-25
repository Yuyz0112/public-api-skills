# digital-experience-monitoring_test_stat_over_time

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `avg` | integer | No | average observed in the time period |
| `max` | integer | No | highest observed in the time period |
| `min` | integer | No | lowest observed in the time period |
| `slots` | object[] | Yes |  |

## Nested Fields

### `slots`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `timestamp` | string | Yes |  |
| `value` | integer | Yes |  |


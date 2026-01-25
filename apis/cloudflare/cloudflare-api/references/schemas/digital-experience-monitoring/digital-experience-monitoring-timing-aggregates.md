# digital-experience-monitoring_timing_aggregates

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `avgMs` | integer | No |  |
| `history` | digital-experience-monitoring_aggregate_stat[] | Yes |  |
| `overTime` | object | No |  |

## Nested Fields

### `overTime`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `timePeriod` | [digital-experience-monitoring_aggregate_time_period](digital-experience-monitoring-aggregate-time-period.md) | Yes |  |
| `values` | digital-experience-monitoring_aggregate_time_slot[] | Yes |  |


# SupportHours

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `type` | enum: fixed_time_per_day | No | The type of support hours |
| `time_zone` | string (activesupport-time-zone) | No | The time zone for the support hours |
| `days_of_week` | integer[] | No |  |
| `start_time` | string (time) | No | The support hours' starting time of day (date portion is ignored) |
| `end_time` | string (time) | No | The support hours' ending time of day (date portion is ignored) |


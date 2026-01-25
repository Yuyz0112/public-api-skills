# Restriction

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `type` | enum: daily_restriction, weekly_restriction | Yes | Specify the types of `restriction`. |
| `duration_seconds` | integer | Yes | The duration of the restriction in seconds. |
| `start_time_of_day` | string (partial-time) | Yes | The start time in HH:mm:ss format. |
| `start_day_of_week` | integer | No | Only required for use with a `weekly_restriction` restriction type. The first day of the weekly rotation schedule as [ISO 8601 day](https://en.wikipedia.org/wiki/ISO_week_date) (1 is Monday, etc.) |


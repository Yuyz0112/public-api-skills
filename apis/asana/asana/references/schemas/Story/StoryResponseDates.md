# StoryResponseDates

*Conditional*

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `start_on` | string (date) | No | The day on which work for this goal begins, or null if the goal has no start date. This takes a date with `YYYY-MM-DD` format, and cannot be set unless there is an accompanying due date. |
| `due_at` | string (date-time) | No | The UTC date and time on which this task is due, or null if the task has no due time. This takes an ISO 8601 date string in UTC and should not be used together with `due_on`. |
| `due_on` | string (date) | No | The localized day on which this goal is due. This takes a date with format `YYYY-MM-DD`. |


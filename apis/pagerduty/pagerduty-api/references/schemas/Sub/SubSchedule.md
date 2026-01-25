# SubSchedule

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `name` | enum: Final Schedule, Overrides | Yes | The name of the subschedule |
| `rendered_schedule_entries` | ScheduleLayerEntry[] | No | This is a list of entries on the computed layer for the current time range. Since or until must be set in order for this field to be populated. |
| `rendered_coverage_percentage` | number | No | The percentage of the time range covered by this layer. Returns null unless since or until are set. |


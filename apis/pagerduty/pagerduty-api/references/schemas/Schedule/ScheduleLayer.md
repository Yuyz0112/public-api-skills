# ScheduleLayer

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | string | No |  |
| `start` | string (date-time) | Yes | The start time of this layer. |
| `end` | string (date-time) | No | The end time of this layer. If `null`, the layer does not end. |
| `users` | ScheduleLayerUser[] | Yes | The ordered list of users on this layer. The position of the user on the list determines their order in the layer. |
| `restrictions` | Restriction[] | No | An array of restrictions for the layer. A restriction is a limit on which period of the day or week the schedule layer can accept assignments. Restrictions respect the `time_zone` parameter of the request. |
| `rotation_virtual_start` | string (date-time) | Yes | The effective start time of the layer. This can be before the start time of the schedule. |
| `rotation_turn_length_seconds` | integer | Yes | The duration of each on-call shift in seconds. |
| `name` | string | No | The name of the schedule layer. |
| `rendered_schedule_entries` | ScheduleLayerEntry[] | No | This is a list of entries on the computed layer for the current time range. Since or until must be set in order for this field to be populated. |
| `rendered_coverage_percentage` | number | No | The percentage of the time range covered by this layer. Returns null unless since or until are set. |


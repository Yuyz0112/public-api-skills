# CreateTimeTrackingEntryRequest

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `duration_minutes` | integer | No | Time in minutes tracked by the entry. Must be greater than 0 |
| `entered_on` | string (date) | No | *Optional*. The day that this entry is logged on. Defaults to today if not specified |
| `attributable_to` | string | No | *Optional*. The gid of the project which the time is attributable to. |


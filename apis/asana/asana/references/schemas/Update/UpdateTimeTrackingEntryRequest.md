# UpdateTimeTrackingEntryRequest

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `duration_minutes` | integer | No | *Optional*. Time in minutes tracked by the entry |
| `entered_on` | string (date) | No | *Optional*. The day that this entry is logged on. Defaults to today if no day specified |
| `attributable_to` | string | No | *Optional*. The gid of the project which the time is attributable to. |


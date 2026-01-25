# ScheduleLayerEntry

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `user` | [UserReference](UserReference.md) | No |  |
| `start` | string (date-time) | Yes | The start time of this entry. |
| `end` | string (date-time) | Yes | The end time of this entry. If null, the entry does not end. |


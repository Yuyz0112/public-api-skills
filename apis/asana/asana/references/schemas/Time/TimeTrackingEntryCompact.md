# TimeTrackingEntryCompact

A generic Asana Resource, containing a globally unique identifier.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `gid` | string | No | Globally unique identifier of the resource, as a string. |
| `resource_type` | string | No | The base type of this resource. |
| `duration_minutes` | integer | No | Time in minutes tracked by the entry. |
| `entered_on` | string (date) | No | The day that this entry is logged on. |
| `attributable_to` | any | No |  |
| `created_by` | [UserCompact](UserCompact.md) | No |  |


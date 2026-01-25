# ResourceExportResponse

A generic Asana Resource, containing a globally unique identifier.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `gid` | string | No | Globally unique identifier of the resource, as a string. |
| `resource_type` | string | No | The base type of this resource. |
| `resource_subtype` | string | No | A *resource_export* object represents a request to bulk export objects for one or more resources. |
| `status` | enum: not_started, in_progress, succeeded... | No | The current status of this job. |
| `new_resource_export` | [ResourceExportCompact](ResourceExportCompact.md) | No |  |


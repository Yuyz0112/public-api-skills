# GraphExportResponse

A generic Asana Resource, containing a globally unique identifier.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `gid` | string | No | Globally unique identifier of the resource, as a string. |
| `resource_type` | string | No | The base type of this resource. |
| `resource_subtype` | string | No | A *graph_export* object represents a request to export the data starting from a parent object |
| `status` | enum: not_started, in_progress, succeeded... | No | The current status of this job. |
| `new_graph_export` | [GraphExportCompact](GraphExportCompact.md) | No |  |


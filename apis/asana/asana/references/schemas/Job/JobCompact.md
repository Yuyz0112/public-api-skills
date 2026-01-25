# JobCompact

A *job* is an object representing a process that handles asynchronous work.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `gid` | string | No | Globally unique identifier of the resource, as a string. |
| `resource_type` | string | No | The base type of this resource. |
| `resource_subtype` | string | No | The subtype of this resource. Different subtypes retain many of the same fields and behavior, but may render differently in Asana or represent resources with different semantic meaning. |
| `status` | enum: not_started, in_progress, succeeded... | No | The current status of this job. |
| `new_project` | [ProjectCompact](ProjectCompact.md) | No |  |
| `new_task` | any | No |  |
| `new_project_template` | [ProjectTemplateCompact](ProjectTemplateCompact.md) | No |  |
| `new_graph_export` | [GraphExportCompact](GraphExportCompact.md) | No |  |
| `new_resource_export` | [ResourceExportCompact](ResourceExportCompact.md) | No |  |


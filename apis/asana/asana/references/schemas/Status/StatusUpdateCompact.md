# StatusUpdateCompact

A *status update* is an update on the progress of a particular project, portfolio, or goal, and is sent out to all of its parent's followers when created. These updates include both text describing the update and a `status_type` intended to represent the overall state of the project.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `gid` | string | No | Globally unique identifier of the resource, as a string. |
| `resource_type` | string | No | The base type of this resource. |
| `title` | string | No | The title of the status update. |
| `resource_subtype` | enum: project_status_update, portfolio_status_update, goal_status_update | No | The subtype of this resource. Different subtypes retain many of the same fields and behavior, but may render differently in Asana or represent resources with different semantic meaning.
The `resource_subtype`s for `status` objects represent the type of their parent. |


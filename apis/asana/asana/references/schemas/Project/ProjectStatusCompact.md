# ProjectStatusCompact

*Deprecated: new integrations should prefer the `status_update` resource.*
A *project status* is an update on the progress of a particular project, and is sent out to all project followers when created. These updates include both text describing the update and a color code intended to represent the overall state of the project: "green" for projects that are on track, "yellow" for projects at risk, and "red" for projects that are behind.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `gid` | string | No | Globally unique identifier of the resource, as a string. |
| `resource_type` | string | No | The base type of this resource. |
| `title` | string | No | The title of the project status update. |


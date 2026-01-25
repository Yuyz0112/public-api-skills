# GoalBase

A generic Asana Resource, containing a globally unique identifier.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `gid` | string | No | Globally unique identifier of the resource, as a string. |
| `resource_type` | string | No | The base type of this resource. |
| `name` | string | No | The name of the goal. |
| `html_notes` | string | No | The notes of the goal with formatting as HTML. |
| `notes` | string | No | Free-form textual information associated with the goal (i.e. its description). |
| `due_on` | string | No | The localized day on which this goal is due. This takes a date with format `YYYY-MM-DD`. |
| `start_on` | string | No | The day on which work for this goal begins, or null if the goal has no start date. This takes a date with `YYYY-MM-DD` format, and cannot be set unless there is an accompanying due date. |
| `is_workspace_level` | boolean | No | *Conditional*. This property is only present when the `workspace` provided is an organization. Whether the goal belongs to the `workspace` (and is listed as part of the workspace’s goals) or not. If it isn’t a workspace-level goal, it is a team-level goal, and is associated with the goal’s team. |
| `liked` | boolean | No | True if the goal is liked by the authorized user, false if not. |


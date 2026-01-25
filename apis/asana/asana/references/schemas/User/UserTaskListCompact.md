# UserTaskListCompact

A user task list represents the tasks assigned to a particular user. It provides API access to a user’s [My tasks](https://asana.com/guide/help/fundamentals/my-tasks) view in Asana.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `gid` | string | No | Globally unique identifier of the resource, as a string. |
| `resource_type` | string | No | The base type of this resource. |
| `name` | string | No | The name of the user task list. |
| `owner` | any | No | The owner of the user task list, i.e. the person whose My Tasks is represented by this resource. |
| `workspace` | any | No | The workspace in which the user task list is located. |


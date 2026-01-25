# GET /tasks

**Resource:** [Tasks](../resources/Tasks.md)
**Get multiple tasks**
**Operation ID:** `getTasks`

<b>Required scope: </b><code>tasks:read</code>

Returns the compact task records for some filtered set of tasks. Use one or more of the parameters provided to filter the tasks returned. You must specify a `project` or `tag` if you do not specify `assignee` and `workspace`.

For more complex task retrieval, use [workspaces/{workspace_gid}/tasks/search](/reference/searchtasksforworkspace).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `assignee` | query | string | No | The assignee to filter tasks on. If searching for unassigned tasks, assignee.any = null can be specified.
*Note: If you specify `assignee`, you must also specify the `workspace` to filter on.* |
| `project` | query | string | No | The project to filter tasks on. |
| `section` | query | string | No | The section to filter tasks on. |
| `workspace` | query | string | No | The workspace to filter tasks on.
*Note: If you specify `workspace`, you must also specify the `assignee` to filter on.* |
| `completed_since` | query | string (date-time) | No | Only return tasks that are either incomplete or that have been completed since this time. |
| `modified_since` | query | string (date-time) | No | Only return tasks that have been modified since the given time.

*Note: A task is considered “modified” if any of its properties
change, or associations between it and other objects are modified
(e.g.  a task being added to a project). A task is not considered
modified just because another object it is associated with (e.g. a
subtask) is modified. Actions that count as modifying the task
include assigning, renaming, completing, and adding stories.* |
| `opt_fields` | query | string[] | No | This endpoint returns a resource which excludes some properties by default. To include those optional properties, set this query parameter to a comma-separated list of the properties you wish to include. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successfully retrieved requested tasks. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

## Security

- **personalAccessToken**
- **oauth2**: tasks:read

# POST /tasks/{task_gid}/setParent

**Resource:** [Tasks](../resources/Tasks.md)
**Set the parent of a task**
**Operation ID:** `setParentForTask`

<b>Required scope: </b><code>tasks:write</code>

Updates the parent of a given task. This endpoint can be used to make a task a subtask of another task, or to remove its existing parent.
When using `insert_before` and `insert_after`, at most one of those two options can be specified, and they must already be subtasks of the parent.
Returns the complete, updated record of the affected [task](/reference/tasks#/task).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `opt_fields` | query | string[] | No | This endpoint returns a resource which excludes some properties by default. To include those optional properties, set this query parameter to a comma-separated list of the properties you wish to include. |

## Request Body

The new parent of the subtask.

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successfully changed the parent of the specified subtask. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

## Security

- **personalAccessToken**
- **oauth2**: tasks:write

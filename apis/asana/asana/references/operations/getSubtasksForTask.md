# GET /tasks/{task_gid}/subtasks

**Resource:** [Tasks](../resources/Tasks.md)
**Get subtasks from a task**
**Operation ID:** `getSubtasksForTask`

<b>Required scope: </b><code>tasks:read</code>

Returns a compact representation of all of the subtasks of a task.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `opt_fields` | query | string[] | No | This endpoint returns a resource which excludes some properties by default. To include those optional properties, set this query parameter to a comma-separated list of the properties you wish to include. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successfully retrieved the specified task's subtasks. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

## Security

- **personalAccessToken**
- **oauth2**: tasks:read

# POST /tasks/{task_gid}/removeProject

**Resource:** [Tasks](../resources/Tasks.md)
**Remove a project from a task**
**Operation ID:** `removeProjectForTask`

<b>Required scope: </b><code>tasks:write</code>

Removes the task from the specified project. The task will still exist in
the system, but it will not be in the project anymore.

Returns an empty data block.

## Request Body

The project to remove the task from.

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successfully removed the specified project from the task. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

## Security

- **personalAccessToken**
- **oauth2**: tasks:write

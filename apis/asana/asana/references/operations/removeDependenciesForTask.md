# POST /tasks/{task_gid}/removeDependencies

**Resource:** [Tasks](../resources/Tasks.md)
**Unlink dependencies from a task**
**Operation ID:** `removeDependenciesForTask`

<b>Required scope: </b><code>tasks:write</code>

Unlinks a set of dependencies from this task.

## Request Body

The list of tasks to unlink as dependencies.

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successfully unlinked the dependencies from the specified task. |
| 400 | (reference) |
| 401 | (reference) |
| 402 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

## Security

- **personalAccessToken**
- **oauth2**: tasks:write

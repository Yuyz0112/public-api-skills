# POST /tasks/{task_gid}/removeDependents

**Resource:** [Tasks](../resources/Tasks.md)
**Unlink dependents from a task**
**Operation ID:** `removeDependentsForTask`

<b>Required scope: </b><code>tasks:write</code>

Unlinks a set of dependents from this task.

## Request Body

The list of tasks to remove as dependents.

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successfully unlinked the specified tasks as dependents. |
| 400 | (reference) |
| 401 | (reference) |
| 402 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

## Security

- **personalAccessToken**
- **oauth2**: tasks:write

# POST /tasks/{task_gid}/addDependencies

**Resource:** [Tasks](../resources/Tasks.md)
**Set dependencies for a task**
**Operation ID:** `addDependenciesForTask`

<b>Required scope: </b><code>tasks:write</code>

Marks a set of tasks as dependencies of this task, if they are not already dependencies. *A task can have at most 30 dependents and dependencies combined*.

## Request Body

The list of tasks to set as dependencies.

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successfully set the specified dependencies on the task. |
| 400 | (reference) |
| 401 | (reference) |
| 402 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

## Security

- **personalAccessToken**
- **oauth2**: tasks:write

# POST /tasks/{task_gid}/addDependents

**Resource:** [Tasks](../resources/Tasks.md)
**Set dependents for a task**
**Operation ID:** `addDependentsForTask`

<b>Required scope: </b><code>tasks:write</code>

Marks a set of tasks as dependents of this task, if they are not already dependents. *A task can have at most 30 dependents and dependencies combined*.

## Request Body

The list of tasks to add as dependents.

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successfully set the specified dependents on the given task. |
| 400 | (reference) |
| 401 | (reference) |
| 402 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

## Security

- **personalAccessToken**
- **oauth2**: tasks:write

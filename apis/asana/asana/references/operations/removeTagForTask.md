# POST /tasks/{task_gid}/removeTag

**Resource:** [Tasks](../resources/Tasks.md)
**Remove a tag from a task**
**Operation ID:** `removeTagForTask`

<b>Required scope: </b><code>tasks:write</code>

Removes a tag from a task. Returns an empty data block.

## Request Body

The tag to remove from the task.

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successfully removed the specified tag from the task. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

## Security

- **personalAccessToken**
- **oauth2**: tasks:write

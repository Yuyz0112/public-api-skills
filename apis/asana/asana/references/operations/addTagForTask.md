# POST /tasks/{task_gid}/addTag

**Resource:** [Tasks](../resources/Tasks.md)
**Add a tag to a task**
**Operation ID:** `addTagForTask`

<b>Required scope: </b><code>tasks:write</code>

Adds a tag to a task. Returns an empty data block.

## Request Body

The tag to add to the task.

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successfully added the specified tag to the task. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

## Security

- **personalAccessToken**
- **oauth2**: tasks:write

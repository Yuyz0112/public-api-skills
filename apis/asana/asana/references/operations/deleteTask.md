# DELETE /tasks/{task_gid}

**Resource:** [Tasks](../resources/Tasks.md)
**Delete a task**
**Operation ID:** `deleteTask`

<b>Required scope: </b><code>tasks:delete</code>

A specific, existing task can be deleted by making a DELETE request on
the URL for that task. Deleted tasks go into the “trash” of the user
making the delete request. Tasks can be recovered from the trash within a
period of 30 days; afterward they are completely removed from the system.

Returns an empty data record.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successfully deleted the specified task. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

## Security

- **personalAccessToken**
- **oauth2**: tasks:delete

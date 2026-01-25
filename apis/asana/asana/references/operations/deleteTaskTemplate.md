# DELETE /task_templates/{task_template_gid}

**Resource:** [Task templates](../resources/Task-templates.md)
**Delete a task template**
**Operation ID:** `deleteTaskTemplate`

A specific, existing task template can be deleted by making a DELETE request on the URL for that task template. Returns an empty data record.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successfully deleted the specified task template. |
| 400 | (reference) |
| 401 | (reference) |
| 402 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

## Security

- **personalAccessToken**
- **oauth2**

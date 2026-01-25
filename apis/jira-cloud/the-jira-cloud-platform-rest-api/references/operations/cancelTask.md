# POST /rest/api/3/task/{taskId}/cancel

**Resource:** [Tasks](../resources/Tasks.md)
**Cancel task**
**Operation ID:** `cancelTask`

Cancels a task.

**[Permissions](#permissions) required:** either of:

 *  *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg).
 *  Creator of the task.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `taskId` | path | string | Yes | The ID of the task. |

## Responses

| Status | Description |
|--------|-------------|
| 202 | Returned if the request is successful. |
| 400 | Returned if cancellation of the task is not possible. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 403 | Returned if the user does not have the necessary permission. |
| 404 | Returned if the task is not found. |

## Security

- **basicAuth**
- **OAuth2**: write:jira-work

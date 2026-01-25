# DELETE /rest/api/3/priority/{id}

**Resource:** [Issue priorities](../resources/Issue-priorities.md)
**Delete priority**
**Operation ID:** `deletePriority`

Deletes an issue priority.

This operation is [asynchronous](#async). Follow the `location` link in the response to determine the status of the task and use [Get task](#api-rest-api-3-task-taskId-get) to obtain subsequent updates.

**[Permissions](#permissions) required:** *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The ID of the issue priority. |

## Responses

| Status | Description |
|--------|-------------|
| 303 | Returned if the request is successful. |
| 400 | Returned if the request isn't valid. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 403 | Returned if the user doesn't have the necessary permission. |
| 404 | Returned if the issue priority isn't found. |
| 409 | Returned if a task to delete the issue priority is already running. |

## Security

- **basicAuth**
- **OAuth2**: manage:jira-configuration

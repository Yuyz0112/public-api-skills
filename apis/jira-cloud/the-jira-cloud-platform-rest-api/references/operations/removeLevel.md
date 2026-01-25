# DELETE /rest/api/3/issuesecurityschemes/{schemeId}/level/{levelId}

**Resource:** [Issue security schemes](../resources/Issue-security-schemes.md)
**Remove issue security level**
**Operation ID:** `removeLevel`

Deletes an issue security level.

This operation is [asynchronous](#async). Follow the `location` link in the response to determine the status of the task and use [Get task](#api-rest-api-3-task-taskId-get) to obtain subsequent updates.

**[Permissions](#permissions) required:** *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `schemeId` | path | string | Yes | The ID of the issue security scheme. |
| `levelId` | path | string | Yes | The ID of the issue security level to remove. |
| `replaceWith` | query | string | No | The ID of the issue security level that will replace the currently selected level. |

## Responses

| Status | Description |
|--------|-------------|
| 303 | Returned if the request is successful. |
| 400 | Returned if the request isn't valid. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 403 | Returned if the user doesn't have the necessary permission. |
| 404 | Returned if the issue security level isn't found. |
| 409 | Returned if a task to remove the issue security level is already running. |

## Security

- **basicAuth**
- **OAuth2**: manage:jira-configuration

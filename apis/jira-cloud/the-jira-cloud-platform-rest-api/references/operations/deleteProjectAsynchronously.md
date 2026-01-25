# POST /rest/api/3/project/{projectIdOrKey}/delete

**Resource:** [Projects](../resources/Projects.md)
**Delete project asynchronously**
**Operation ID:** `deleteProjectAsynchronously`

Deletes a project asynchronously.

This operation is:

 *  transactional, that is, if part of the delete fails the project is not deleted.
 *  [asynchronous](#async). Follow the `location` link in the response to determine the status of the task and use [Get task](#api-rest-api-3-task-taskId-get) to obtain subsequent updates.

**[Permissions](#permissions) required:** *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `projectIdOrKey` | path | string | Yes | The project ID or project key (case sensitive). |

## Responses

| Status | Description |
|--------|-------------|
| 303 | Returned if the request is successful. |
| 400 | Returned if the request is not valid. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 404 | Returned if the project is not found or the user does not have the necessary permission. |

## Security

- **basicAuth**
- **OAuth2**: manage:jira-configuration

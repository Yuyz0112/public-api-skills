# DELETE /rest/api/3/role/{id}

**Resource:** [Project roles](../resources/Project-roles.md)
**Delete project role**
**Operation ID:** `deleteProjectRole`

Deletes a project role. You must specify a replacement project role if you wish to delete a project role that is in use.

**[Permissions](#permissions) required:** *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | integer (int64) | Yes | The ID of the project role to delete. Use [Get all project roles](#api-rest-api-3-role-get) to get a list of project role IDs. |
| `swap` | query | integer (int64) | No | The ID of the project role that will replace the one being deleted. The swap will attempt to swap the role in schemes (notifications, permissions, issue security), workflows, worklogs and comments. |

## Responses

| Status | Description |
|--------|-------------|
| 204 | Returned if the request is successful. |
| 400 | Returned if the request is invalid or if the replacement project role is not found. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 403 | Returned if the user does not have administrative permissions. |
| 404 | Returned if the project role being deleted is not found. |
| 409 | Returned if the project role being deleted is in use and a replacement project role is not specified in the request. |

## Security

- **basicAuth**
- **OAuth2**: manage:jira-configuration

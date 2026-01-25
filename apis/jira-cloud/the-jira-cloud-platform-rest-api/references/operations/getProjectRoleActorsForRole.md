# GET /rest/api/3/role/{id}/actors

**Resource:** [Project role actors](../resources/Project-role-actors.md)
**Get default actors for project role**
**Operation ID:** `getProjectRoleActorsForRole`

Returns the [default actors](#api-rest-api-3-resolution-get) for the project role.

**[Permissions](#permissions) required:** *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | integer (int64) | Yes | The ID of the project role. Use [Get all project roles](#api-rest-api-3-role-get) to get a list of project role IDs. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 400 | Returned if the request is invalid. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 403 | Returned if the user does not have administrative permissions. |
| 404 | Returned if the project role is not found. |

**Success Response Schema:**

[ProjectRole](../schemas/Project/ProjectRole.md)

## Security

- **basicAuth**
- **OAuth2**: manage:jira-configuration

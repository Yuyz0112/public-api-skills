# PUT /rest/api/3/role/{id}

**Resource:** [Project roles](../resources/Project-roles.md)
**Fully update project role**
**Operation ID:** `fullyUpdateProjectRole`

Updates the project role's name and description. You must include both a name and a description in the request.

**[Permissions](#permissions) required:** *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | integer (int64) | Yes | The ID of the project role. Use [Get all project roles](#api-rest-api-3-role-get) to get a list of project role IDs. |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [CreateUpdateRoleRequestBean](../schemas/Create/CreateUpdateRoleRequestBean.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 400 | Returned if the request is not valid. The `name` cannot be empty or start or end with whitespace. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 403 | Returned if the user does not have administrative permissions. |
| 404 | Returned if the project role is not found. |

**Success Response Schema:**

[ProjectRole](../schemas/Project/ProjectRole.md)

## Security

- **basicAuth**
- **OAuth2**: manage:jira-configuration

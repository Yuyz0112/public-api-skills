# POST /rest/api/3/role/{id}/actors

**Resource:** [Project role actors](../resources/Project-role-actors.md)
**Add default actors to project role**
**Operation ID:** `addProjectRoleActorsToRole`

Adds [default actors](#api-rest-api-3-resolution-get) to a role. You may add groups or users, but you cannot add groups and users in the same request.

Changing a project role's default actors does not affect project role members for projects already created.

**[Permissions](#permissions) required:** *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | integer (int64) | Yes | The ID of the project role. Use [Get all project roles](#api-rest-api-3-role-get) to get a list of project role IDs. |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [ActorInputBean](../schemas/Actor/ActorInputBean.md)

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

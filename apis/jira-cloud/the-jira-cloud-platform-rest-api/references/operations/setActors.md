# PUT /rest/api/3/project/{projectIdOrKey}/role/{id}

**Resource:** [Project role actors](../resources/Project-role-actors.md)
**Set actors for project role**
**Operation ID:** `setActors`

Sets the actors for a project role for a project, replacing all existing actors.

To add actors to the project without overwriting the existing list, use [Add actors to project role](#api-rest-api-3-project-projectIdOrKey-role-id-post).

**[Permissions](#permissions) required:** *Administer Projects* [project permission](https://confluence.atlassian.com/x/yodKLg) for the project or *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `projectIdOrKey` | path | string | Yes | The project ID or project key (case sensitive). |
| `id` | path | integer (int64) | Yes | The ID of the project role. Use [Get all project roles](#api-rest-api-3-role-get) to get a list of project role IDs. |

## Request Body

The groups or users to associate with the project role for this project. Provide the user account ID, group name, or group ID. As a group's name can change, use of group ID is recommended.

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [ProjectRoleActorsUpdateBean](../schemas/Project/ProjectRoleActorsUpdateBean.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. The complete list of actors for the project is returned. |
| 400 | Returned if the request is not valid. |
| 401 | Returned if the authentication credentials are incorrect or missing or if the calling user lacks administrative permissions for the project. |
| 404 | Returned if:

 *  the project is not found.
 *  a user or group is not found.
 *  a group or user is not active. |

**Success Response Schema:**

[ProjectRole](../schemas/Project/ProjectRole.md)

## Security

- **basicAuth**
- **OAuth2**: manage:jira-project

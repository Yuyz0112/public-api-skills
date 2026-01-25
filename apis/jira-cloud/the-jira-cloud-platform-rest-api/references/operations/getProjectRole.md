# GET /rest/api/3/project/{projectIdOrKey}/role/{id}

**Resource:** [Project roles](../resources/Project-roles.md)
**Get project role for project**
**Operation ID:** `getProjectRole`

Returns a project role's details and actors associated with the project. The list of actors is sorted by display name.

To check whether a user belongs to a role based on their group memberships, use [Get user](#api-rest-api-3-user-get) with the `groups` expand parameter selected. Then check whether the user keys and groups match with the actors returned for the project.

This operation can be accessed anonymously.

**[Permissions](#permissions) required:** *Administer Projects* [project permission](https://confluence.atlassian.com/x/yodKLg) for the project or *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `projectIdOrKey` | path | string | Yes | The project ID or project key (case sensitive). |
| `id` | path | integer (int64) | Yes | The ID of the project role. Use [Get all project roles](#api-rest-api-3-role-get) to get a list of project role IDs. |
| `excludeInactiveUsers` | query | boolean | No | Exclude inactive users. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 400 | Returned if the request is not valid. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 404 | Returned if:

 *  the project or project role is not found.
 *  the user does not have administrative permission. |

**Success Response Schema:**

[ProjectRole](../schemas/Project/ProjectRole.md)

## Security

- **basicAuth**
- **OAuth2**: read:jira-work

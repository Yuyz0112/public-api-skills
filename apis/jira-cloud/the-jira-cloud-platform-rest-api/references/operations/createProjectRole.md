# POST /rest/api/3/role

**Resource:** [Project roles](../resources/Project-roles.md)
**Create project role**
**Operation ID:** `createProjectRole`

Creates a new project role with no [default actors](#api-rest-api-3-resolution-get). You can use the [Add default actors to project role](#api-rest-api-3-role-id-actors-post) operation to add default actors to the project role after creating it.

*Note that although a new project role is available to all projects upon creation, any default actors that are associated with the project role are not added to projects that existed prior to the role being created.*<

**[Permissions](#permissions) required:** *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg).

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
| 409 | Returned if a project role with the provided name already exists. |

**Success Response Schema:**

[ProjectRole](../schemas/Project/ProjectRole.md)

## Security

- **basicAuth**
- **OAuth2**: manage:jira-configuration

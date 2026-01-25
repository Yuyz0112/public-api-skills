# POST /rest/api/3/permissions/project

**Resource:** [Permissions](../resources/Permissions.md)
**Get permitted projects**
**Operation ID:** `getPermittedProjects`

Returns all the projects where the user is granted a list of project permissions.

This operation can be accessed anonymously.

**[Permissions](#permissions) required:** None.

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [PermissionsKeysBean](../schemas/Permissions/PermissionsKeysBean.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 400 | Returned if a project permission is not found. |
| 401 | Returned if the authentication credentials are incorrect or missing. |

**Success Response Schema:**

[PermittedProjects](../schemas/Permitted/PermittedProjects.md)

## Security

- **basicAuth**
- **OAuth2**: read:jira-work

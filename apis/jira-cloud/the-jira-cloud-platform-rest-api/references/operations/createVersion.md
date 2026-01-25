# POST /rest/api/3/version

**Resource:** [Project versions](../resources/Project-versions.md)
**Create version**
**Operation ID:** `createVersion`

Creates a project version.

This operation can be accessed anonymously.

**[Permissions](#permissions) required:** *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg) or *Administer Projects* [project permission](https://confluence.atlassian.com/x/yodKLg) for the project the version is added to.

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [Version](../schemas/Version/Version.md)

## Responses

| Status | Description |
|--------|-------------|
| 201 | Returned if the request is successful. |
| 400 | Returned if the request is invalid. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 404 | Returned if:

 *  the project is not found.
 *  the user does not have the required permissions. |

**Success Response Schema:**

[Version](../schemas/Version/Version.md)

## Security

- **basicAuth**
- **OAuth2**: manage:jira-project

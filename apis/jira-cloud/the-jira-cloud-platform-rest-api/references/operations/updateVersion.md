# PUT /rest/api/3/version/{id}

**Resource:** [Project versions](../resources/Project-versions.md)
**Update version**
**Operation ID:** `updateVersion`

Updates a project version.

This operation can be accessed anonymously.

**[Permissions](#permissions) required:** *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg) or *Administer Projects* [project permission](https://confluence.atlassian.com/x/yodKLg) for the project that contains the version.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The ID of the version. |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [Version](../schemas/Version/Version.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 400 | Returned if:

 *  the request is invalid.
 *  the user does not have the required permissions. |
| 401 | Returned if the authentication credentials are incorrect. |
| 404 | Returned if the version is not found. |

**Success Response Schema:**

[Version](../schemas/Version/Version.md)

## Security

- **basicAuth**
- **OAuth2**: manage:jira-project

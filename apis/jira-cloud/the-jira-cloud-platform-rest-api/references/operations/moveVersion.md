# POST /rest/api/3/version/{id}/move

**Resource:** [Project versions](../resources/Project-versions.md)
**Move version**
**Operation ID:** `moveVersion`

Modifies the version's sequence within the project, which affects the display order of the versions in Jira.

This operation can be accessed anonymously.

**[Permissions](#permissions) required:** *Browse projects* project permission for the project that contains the version.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The ID of the version to be moved. |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [VersionMoveBean](../schemas/Version/VersionMoveBean.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 400 | Returned if:

 *  no body parameters are provided.
 *  `after` and `position` are provided.
 *  `position` is invalid. |
| 401 | Returned if:

 *  the authentication credentials are incorrect or missing
 *  the user does not have the required commissions. |
| 404 | Returned if the version or move after version are not found. |

**Success Response Schema:**

[Version](../schemas/Version/Version.md)

## Security

- **basicAuth**
- **OAuth2**: manage:jira-project

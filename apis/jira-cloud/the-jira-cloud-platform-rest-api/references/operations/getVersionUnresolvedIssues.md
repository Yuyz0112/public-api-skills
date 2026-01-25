# GET /rest/api/3/version/{id}/unresolvedIssueCount

**Resource:** [Project versions](../resources/Project-versions.md)
**Get version's unresolved issues count**
**Operation ID:** `getVersionUnresolvedIssues`

Returns counts of the issues and unresolved issues for the project version.

This operation can be accessed anonymously.

**[Permissions](#permissions) required:** *Browse projects* project permission for the project that contains the version.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The ID of the version. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 404 | Returned if:

 *  the version is not found.
 *  the user does not have the required permissions. |

**Success Response Schema:**

[VersionUnresolvedIssuesCount](../schemas/Version/VersionUnresolvedIssuesCount.md)

## Security

- **basicAuth**
- **OAuth2**: read:jira-work

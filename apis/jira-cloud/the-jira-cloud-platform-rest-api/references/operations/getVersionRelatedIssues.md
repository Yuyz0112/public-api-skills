# GET /rest/api/3/version/{id}/relatedIssueCounts

**Resource:** [Project versions](../resources/Project-versions.md)
**Get version's related issues count**
**Operation ID:** `getVersionRelatedIssues`

Returns the following counts for a version:

 *  Number of issues where the `fixVersion` is set to the version.
 *  Number of issues where the `affectedVersion` is set to the version.
 *  Number of issues where a version custom field is set to the version.

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
| 401 | Returned if the authentication credentials are incorrect. |
| 404 | Returned if:

 *  the version is not found.
 *  the user does not have the required permissions. |

**Success Response Schema:**

[VersionIssueCounts](../schemas/Version/VersionIssueCounts.md)

## Security

- **basicAuth**
- **OAuth2**: read:jira-work

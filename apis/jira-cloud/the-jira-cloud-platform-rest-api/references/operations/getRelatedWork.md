# GET /rest/api/3/version/{id}/relatedwork

**Resource:** [Project versions](../resources/Project-versions.md)
**Get related work**
**Operation ID:** `getRelatedWork`

Returns related work items for the given version id.

This operation can be accessed anonymously.

**[Permissions](#permissions) required:** *Browse projects* [project permission](https://confluence.atlassian.com/x/yodKLg) for the project containing the version.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The ID of the version. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 404 | Returned if the version is not found or the user does not have the necessary permission. |
| 500 | Returned if reading related work fails |

**Success Response Schema:**

Array of [VersionRelatedWork](../schemas/Version/VersionRelatedWork.md)

## Security

- **basicAuth**
- **OAuth2**: read:jira-work

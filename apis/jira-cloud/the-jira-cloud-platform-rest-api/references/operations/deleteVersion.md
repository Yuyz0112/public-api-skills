# DELETE /rest/api/3/version/{id}

**Resource:** [Project versions](../resources/Project-versions.md)
**Delete version**
**Operation ID:** `deleteVersion`
⚠️ **Deprecated**

Deletes a project version.

Deprecated, use [ Delete and replace version](#api-rest-api-3-version-id-removeAndSwap-post) that supports swapping version values in custom fields, in addition to the swapping for `fixVersion` and `affectedVersion` provided in this resource.

Alternative versions can be provided to update issues that use the deleted version in `fixVersion` or `affectedVersion`. If alternatives are not provided, occurrences of `fixVersion` and `affectedVersion` that contain the deleted version are cleared.

This operation can be accessed anonymously.

**[Permissions](#permissions) required:** *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg) or *Administer Projects* [project permission](https://confluence.atlassian.com/x/yodKLg) for the project that contains the version.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The ID of the version. |
| `moveFixIssuesTo` | query | string | No | The ID of the version to update `fixVersion` to when the field contains the deleted version. The replacement version must be in the same project as the version being deleted and cannot be the version being deleted. |
| `moveAffectedIssuesTo` | query | string | No | The ID of the version to update `affectedVersion` to when the field contains the deleted version. The replacement version must be in the same project as the version being deleted and cannot be the version being deleted. |

## Responses

| Status | Description |
|--------|-------------|
| 204 | Returned if the version is deleted. |
| 400 | Returned if the request is invalid. |
| 401 | Returned if:

 *  the authentication credentials are incorrect.
 *  the user does not have the required permissions. |
| 404 | Returned if the version is not found. |

## Security

- **basicAuth**
- **OAuth2**: manage:jira-project

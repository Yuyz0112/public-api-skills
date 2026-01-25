# DELETE /rest/api/3/permissionscheme/{schemeId}

**Resource:** [Permission schemes](../resources/Permission-schemes.md)
**Delete permission scheme**
**Operation ID:** `deletePermissionScheme`

Deletes a permission scheme.

**[Permissions](#permissions) required:** *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `schemeId` | path | integer (int64) | Yes | The ID of the permission scheme being deleted. |

## Responses

| Status | Description |
|--------|-------------|
| 204 | Returned if the permission scheme is deleted. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 403 | Returned if the user does not have the necessary permission. |
| 404 | Returned if the permission scheme is not found. |

## Security

- **basicAuth**
- **OAuth2**: manage:jira-configuration

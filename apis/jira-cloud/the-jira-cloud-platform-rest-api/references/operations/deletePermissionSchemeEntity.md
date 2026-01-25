# DELETE /rest/api/3/permissionscheme/{schemeId}/permission/{permissionId}

**Resource:** [Permission schemes](../resources/Permission-schemes.md)
**Delete permission scheme grant**
**Operation ID:** `deletePermissionSchemeEntity`

Deletes a permission grant from a permission scheme. See [About permission schemes and grants](../api-group-permission-schemes/#about-permission-schemes-and-grants) for more details.

**[Permissions](#permissions) required:** *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `schemeId` | path | integer (int64) | Yes | The ID of the permission scheme to delete the permission grant from. |
| `permissionId` | path | integer (int64) | Yes | The ID of the permission grant to delete. |

## Responses

| Status | Description |
|--------|-------------|
| 204 | Returned if the permission grant is deleted. |
| 400 | Returned if permission grant with the provided ID is not found. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 403 | Returned if the user does not have the necessary permission. |

## Security

- **basicAuth**
- **OAuth2**: manage:jira-configuration

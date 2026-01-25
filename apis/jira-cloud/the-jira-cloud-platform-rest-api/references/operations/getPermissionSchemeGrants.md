# GET /rest/api/3/permissionscheme/{schemeId}/permission

**Resource:** [Permission schemes](../resources/Permission-schemes.md)
**Get permission scheme grants**
**Operation ID:** `getPermissionSchemeGrants`

Returns all permission grants for a permission scheme.

**[Permissions](#permissions) required:** Permission to access Jira.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `schemeId` | path | integer (int64) | Yes | The ID of the permission scheme. |
| `expand` | query | string | No | Use expand to include additional information in the response. This parameter accepts a comma-separated list. Note that permissions are always included when you specify any value. Expand options include:

 *  `permissions` Returns all permission grants for each permission scheme.
 *  `user` Returns information about the user who is granted the permission.
 *  `group` Returns information about the group that is granted the permission.
 *  `projectRole` Returns information about the project role granted the permission.
 *  `field` Returns information about the custom field granted the permission.
 *  `all` Returns all expandable information. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 404 | Returned if the permission schemes is not found or the user does not have the necessary permission. |

**Success Response Schema:**

[PermissionGrants](../schemas/Permission/PermissionGrants.md)

## Security

- **basicAuth**
- **OAuth2**: read:jira-work

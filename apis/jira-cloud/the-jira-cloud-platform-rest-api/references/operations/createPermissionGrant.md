# POST /rest/api/3/permissionscheme/{schemeId}/permission

**Resource:** [Permission schemes](../resources/Permission-schemes.md)
**Create permission grant**
**Operation ID:** `createPermissionGrant`

Creates a permission grant in a permission scheme.

**[Permissions](#permissions) required:** *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `schemeId` | path | integer (int64) | Yes | The ID of the permission scheme in which to create a new permission grant. |
| `expand` | query | string | No | Use expand to include additional information in the response. This parameter accepts a comma-separated list. Note that permissions are always included when you specify any value. Expand options include:

 *  `permissions` Returns all permission grants for each permission scheme.
 *  `user` Returns information about the user who is granted the permission.
 *  `group` Returns information about the group that is granted the permission.
 *  `projectRole` Returns information about the project role granted the permission.
 *  `field` Returns information about the custom field granted the permission.
 *  `all` Returns all expandable information. |

## Request Body

The permission grant to create.

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [PermissionGrant](../schemas/Permission/PermissionGrant.md)

## Responses

| Status | Description |
|--------|-------------|
| 201 | Returned if the scheme permission is created. |
| 400 | Returned if the value for expand is invalid or the same permission grant is present. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 403 | Returned if the user does not have the necessary permission. |

**Success Response Schema:**

[PermissionGrant](../schemas/Permission/PermissionGrant.md)

## Security

- **basicAuth**
- **OAuth2**: manage:jira-configuration

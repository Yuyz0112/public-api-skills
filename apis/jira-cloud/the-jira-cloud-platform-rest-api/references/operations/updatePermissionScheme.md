# PUT /rest/api/3/permissionscheme/{schemeId}

**Resource:** [Permission schemes](../resources/Permission-schemes.md)
**Update permission scheme**
**Operation ID:** `updatePermissionScheme`

Updates a permission scheme. Below are some important things to note when using this resource:

 *  If a permissions list is present in the request, then it is set in the permission scheme, overwriting *all existing* grants.
 *  If you want to update only the name and description, then do not send a permissions list in the request.
 *  Sending an empty list will remove all permission grants from the permission scheme.

If you want to add or delete a permission grant instead of updating the whole list, see [Create permission grant](#api-rest-api-3-permissionscheme-schemeId-permission-post) or [Delete permission scheme entity](#api-rest-api-3-permissionscheme-schemeId-permission-permissionId-delete).

See [About permission schemes and grants](../api-group-permission-schemes/#about-permission-schemes-and-grants) for more details.

**[Permissions](#permissions) required:** *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `schemeId` | path | integer (int64) | Yes | The ID of the permission scheme to update. |
| `expand` | query | string | No | Use expand to include additional information in the response. This parameter accepts a comma-separated list. Note that permissions are always included when you specify any value. Expand options include:

 *  `all` Returns all expandable information.
 *  `field` Returns information about the custom field granted the permission.
 *  `group` Returns information about the group that is granted the permission.
 *  `permissions` Returns all permission grants for each permission scheme.
 *  `projectRole` Returns information about the project role granted the permission.
 *  `user` Returns information about the user who is granted the permission. |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [PermissionScheme](../schemas/Permission/PermissionScheme.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the scheme is updated. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 403 | Returned if:

 *  the user does not have the necessary permission to update permission schemes.
 *  the Jira instance is Jira Core Free or Jira Software Free. Permission schemes cannot be updated on free plans. |
| 404 | Returned if the permission scheme is not found. |

**Success Response Schema:**

[PermissionScheme](../schemas/Permission/PermissionScheme.md)

## Security

- **basicAuth**
- **OAuth2**: manage:jira-configuration

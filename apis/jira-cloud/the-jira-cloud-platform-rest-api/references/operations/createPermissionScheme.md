# POST /rest/api/3/permissionscheme

**Resource:** [Permission schemes](../resources/Permission-schemes.md)
**Create permission scheme**
**Operation ID:** `createPermissionScheme`

Creates a new permission scheme. You can create a permission scheme with or without defining a set of permission grants.

**[Permissions](#permissions) required:** *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `expand` | query | string | No | Use expand to include additional information in the response. This parameter accepts a comma-separated list. Note that permissions are always included when you specify any value. Expand options include:

 *  `all` Returns all expandable information.
 *  `field` Returns information about the custom field granted the permission.
 *  `group` Returns information about the group that is granted the permission.
 *  `permissions` Returns all permission grants for each permission scheme.
 *  `projectRole` Returns information about the project role granted the permission.
 *  `user` Returns information about the user who is granted the permission. |

## Request Body

The permission scheme to create.

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [PermissionScheme](../schemas/Permission/PermissionScheme.md)

## Responses

| Status | Description |
|--------|-------------|
| 201 | Returned if the permission scheme is created. |
| 400 | Returned if the request is invalid. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 403 | Returned if the user does not have the necessary permission or the feature is not available in the Jira plan. |

**Success Response Schema:**

[PermissionScheme](../schemas/Permission/PermissionScheme.md)

## Security

- **basicAuth**
- **OAuth2**: manage:jira-configuration

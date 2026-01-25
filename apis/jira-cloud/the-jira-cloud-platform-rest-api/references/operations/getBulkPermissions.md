# POST /rest/api/3/permissions/check

**Resource:** [Permissions](../resources/Permissions.md)
**Get bulk permissions**
**Operation ID:** `getBulkPermissions`

Returns:

 *  for a list of global permissions, the global permissions granted to a user.
 *  for a list of project permissions and lists of projects and issues, for each project permission a list of the projects and issues a user can access or manipulate.

If no account ID is provided, the operation returns details for the logged in user.

Note that:

 *  Invalid project and issue IDs are ignored.
 *  A maximum of 1000 projects and 1000 issues can be checked.
 *  Null values in `globalPermissions`, `projectPermissions`, `projectPermissions.projects`, and `projectPermissions.issues` are ignored.
 *  Empty strings in `projectPermissions.permissions` are ignored.

**Deprecation notice:** The required OAuth 2.0 scopes will be updated on June 15, 2024.

 *  **Classic**: `read:jira-work`
 *  **Granular**: `read:permission:jira`

This operation can be accessed anonymously.

**[Permissions](#permissions) required:** *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg) to check the permissions for other users, otherwise none. However, Connect apps can make a call from the app server to the product to obtain permission details for any user, without admin permission. This Connect app ability doesn't apply to calls made using AP.request() in a browser.

## Request Body

Details of the permissions to check.

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [BulkPermissionsRequestBean](../schemas/Bulk/BulkPermissionsRequestBean.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 400 | Returned if:

 *  `projectPermissions` is provided without at least one project permission being provided.
 *  an invalid global permission is provided in the global permissions list.
 *  an invalid project permission is provided in the project permissions list.
 *  more than 1000 valid project IDs or more than 1000 valid issue IDs are provided.
 *  an invalid account ID is provided. |
| 403 | Returned if the user does not have the necessary permission. |

**Success Response Schema:**

[BulkPermissionGrants](../schemas/Bulk/BulkPermissionGrants.md)

## Security

- **basicAuth**
- **OAuth2**

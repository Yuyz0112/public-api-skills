# GET /rest/api/3/project/{projectKeyOrId}/permissionscheme

**Resource:** [Project permission schemes](../resources/Project-permission-schemes.md)
**Get assigned permission scheme**
**Operation ID:** `getAssignedPermissionScheme`

Gets the [permission scheme](https://confluence.atlassian.com/x/yodKLg) associated with the project.

**[Permissions](#permissions) required:** *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg) or *Administer projects* [project permission](https://confluence.atlassian.com/x/yodKLg).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `projectKeyOrId` | path | string | Yes | The project ID or project key (case sensitive). |
| `expand` | query | string | No | Use [expand](#expansion) to include additional information in the response. This parameter accepts a comma-separated list. Note that permissions are included when you specify any value. Expand options include:

 *  `all` Returns all expandable information.
 *  `field` Returns information about the custom field granted the permission.
 *  `group` Returns information about the group that is granted the permission.
 *  `permissions` Returns all permission grants for each permission scheme.
 *  `projectRole` Returns information about the project role granted the permission.
 *  `user` Returns information about the user who is granted the permission. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 403 | Returned if the user does not have permission to view the project's configuration. |
| 404 | Returned if the project is not found or the user does not have permission to view the project. |

**Success Response Schema:**

[PermissionScheme](../schemas/Permission/PermissionScheme.md)

## Security

- **basicAuth**
- **OAuth2**: read:jira-work

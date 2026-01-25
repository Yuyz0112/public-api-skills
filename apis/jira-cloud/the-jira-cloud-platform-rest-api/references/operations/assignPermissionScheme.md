# PUT /rest/api/3/project/{projectKeyOrId}/permissionscheme

**Resource:** [Project permission schemes](../resources/Project-permission-schemes.md)
**Assign permission scheme**
**Operation ID:** `assignPermissionScheme`

Assigns a permission scheme with a project. See [Managing project permissions](https://confluence.atlassian.com/x/yodKLg) for more information about permission schemes.

**[Permissions](#permissions) required:** *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg)

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

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [IdBean](../schemas/Id/IdBean.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 403 | Returned if:

 *  the user does not have the necessary permission to edit the project's configuration.
 *  the Jira instance is Jira Core Free or Jira Software Free. Permission schemes cannot be assigned to projects on free plans. |
| 404 | Returned if the project or permission scheme is not found. |

**Success Response Schema:**

[PermissionScheme](../schemas/Permission/PermissionScheme.md)

## Security

- **basicAuth**
- **OAuth2**: manage:jira-project

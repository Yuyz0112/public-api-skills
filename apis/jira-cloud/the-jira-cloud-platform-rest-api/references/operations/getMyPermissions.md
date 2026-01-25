# GET /rest/api/3/mypermissions

**Resource:** [Permissions](../resources/Permissions.md)
**Get my permissions**
**Operation ID:** `getMyPermissions`

Returns a list of permissions indicating which permissions the user has. Details of the user's permissions can be obtained in a global, project, issue or comment context.

The user is reported as having a project permission:

 *  in the global context, if the user has the project permission in any project.
 *  for a project, where the project permission is determined using issue data, if the user meets the permission's criteria for any issue in the project. Otherwise, if the user has the project permission in the project.
 *  for an issue, where a project permission is determined using issue data, if the user has the permission in the issue. Otherwise, if the user has the project permission in the project containing the issue.
 *  for a comment, where the user has both the permission to browse the comment and the project permission for the comment's parent issue. Only the BROWSE\_PROJECTS permission is supported. If a `commentId` is provided whose `permissions` does not equal BROWSE\_PROJECTS, a 400 error will be returned.

This means that users may be shown as having an issue permission (such as EDIT\_ISSUES) in the global context or a project context but may not have the permission for any or all issues. For example, if Reporters have the EDIT\_ISSUES permission a user would be shown as having this permission in the global context or the context of a project, because any user can be a reporter. However, if they are not the user who reported the issue queried they would not have EDIT\_ISSUES permission for that issue.

For [Jira Service Management project permissions](https://support.atlassian.com/jira-cloud-administration/docs/customize-jira-service-management-permissions/), this will be evaluated similarly to a user in the customer portal. For example, if the BROWSE\_PROJECTS permission is granted to Service Project Customer - Portal Access, any users with access to the customer portal will have the BROWSE\_PROJECTS permission.

Global permissions are unaffected by context.

This operation can be accessed anonymously.

**[Permissions](#permissions) required:** None.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `projectKey` | query | string | No | The key of project. Ignored if `projectId` is provided. |
| `projectId` | query | string | No | The ID of project. |
| `issueKey` | query | string | No | The key of the issue. Ignored if `issueId` is provided. |
| `issueId` | query | string | No | The ID of the issue. |
| `permissions` | query | string | No | A list of permission keys. (Required) This parameter accepts a comma-separated list. To get the list of available permissions, use [Get all permissions](#api-rest-api-3-permissions-get). |
| `projectUuid` | query | string | No |  |
| `projectConfigurationUuid` | query | string | No |  |
| `commentId` | query | string | No | The ID of the comment. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 400 | Returned if `permissions` is empty, contains an invalid key, or does not equal BROWSE\_PROJECTS when commentId is provided. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 404 | Returned if the project or issue is not found or the user does not have permission to view the project or issue. |

**Success Response Schema:**

[Permissions](../schemas/Permissions/Permissions.md)

## Security

- **basicAuth**
- **OAuth2**: read:jira-work

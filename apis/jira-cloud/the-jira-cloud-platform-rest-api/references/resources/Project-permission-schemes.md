# Project permission schemes

This resource represents permission schemes for a project. Use this resource to:

 *  get details of a project's issue security levels available to the calling user.
 *  get the permission scheme associated with the project or assign different permission scheme to the project.
 *  get details of a project's issue security scheme.

See [Managing project permissions](https://confluence.atlassian.com/x/yodKLg) for more information about permission schemes.

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/rest/api/3/project/{projectKeyOrId}/issuesecuritylevelscheme` | Get project issue security scheme | [View](../operations/getProjectIssueSecurityScheme.md) |
| GET | `/rest/api/3/project/{projectKeyOrId}/permissionscheme` | Get assigned permission scheme | [View](../operations/getAssignedPermissionScheme.md) |
| PUT | `/rest/api/3/project/{projectKeyOrId}/permissionscheme` | Assign permission scheme | [View](../operations/assignPermissionScheme.md) |
| GET | `/rest/api/3/project/{projectKeyOrId}/securitylevel` | Get project issue security levels | [View](../operations/getSecurityLevelsForProject.md) |

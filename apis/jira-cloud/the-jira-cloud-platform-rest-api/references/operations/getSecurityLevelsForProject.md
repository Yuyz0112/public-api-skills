# GET /rest/api/3/project/{projectKeyOrId}/securitylevel

**Resource:** [Project permission schemes](../resources/Project-permission-schemes.md)
**Get project issue security levels**
**Operation ID:** `getSecurityLevelsForProject`

Returns all [issue security](https://confluence.atlassian.com/x/J4lKLg) levels for the project that the user has access to.

This operation can be accessed anonymously.

**[Permissions](#permissions) required:** *Browse projects* [global permission](https://confluence.atlassian.com/x/x4dKLg) for the project, however, issue security levels are only returned for authenticated user with *Set Issue Security* [global permission](https://confluence.atlassian.com/x/x4dKLg) for the project.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `projectKeyOrId` | path | string | Yes | The project ID or project key (case sensitive). |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 404 | Returned if the project is not found or the user does not have permission to view it. |

**Success Response Schema:**

[ProjectIssueSecurityLevels](../schemas/Project/ProjectIssueSecurityLevels.md)

## Security

- **basicAuth**
- **OAuth2**: read:jira-work

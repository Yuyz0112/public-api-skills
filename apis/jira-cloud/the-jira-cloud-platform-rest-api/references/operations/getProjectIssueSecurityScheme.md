# GET /rest/api/3/project/{projectKeyOrId}/issuesecuritylevelscheme

**Resource:** [Project permission schemes](../resources/Project-permission-schemes.md)
**Get project issue security scheme**
**Operation ID:** `getProjectIssueSecurityScheme`

Returns the [issue security scheme](https://confluence.atlassian.com/x/J4lKLg) associated with the project.

**[Permissions](#permissions) required:** *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg) or the *Administer Projects* [project permission](https://confluence.atlassian.com/x/yodKLg).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `projectKeyOrId` | path | string | Yes | The project ID or project key (case sensitive). |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 400 | Returned if the request is invalid. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 403 | Returned if the project is visible to the user but the user doesn't have administrative permissions. |
| 404 | Returned if the project is not found or the user does not have permission to view it. |

**Success Response Schema:**

[SecurityScheme](../schemas/Security/SecurityScheme.md)

## Security

- **basicAuth**
- **OAuth2**: read:jira-work

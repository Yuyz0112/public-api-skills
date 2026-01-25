# GET /rest/api/3/project/{projectId}/email

**Resource:** [Project email](../resources/Project-email.md)
**Get project's sender email**
**Operation ID:** `getProjectEmail`

Returns the [project's sender email address](https://confluence.atlassian.com/x/dolKLg).

**[Permissions](#permissions) required:** *Browse projects* [project permission](https://confluence.atlassian.com/x/yodKLg) for the project.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `projectId` | path | integer (int64) | Yes | The project ID. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 403 | Returned if the user does not have permission to read project. |
| 404 | Returned if the project or project's sender email address is not found. |

**Success Response Schema:**

[ProjectEmailAddress](../schemas/Project/ProjectEmailAddress.md)

## Security

- **basicAuth**
- **OAuth2**: manage:jira-project

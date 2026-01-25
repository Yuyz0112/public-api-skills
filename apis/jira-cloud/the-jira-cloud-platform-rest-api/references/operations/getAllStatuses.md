# GET /rest/api/3/project/{projectIdOrKey}/statuses

**Resource:** [Projects](../resources/Projects.md)
**Get all statuses for project**
**Operation ID:** `getAllStatuses`

Returns the valid statuses for a project. The statuses are grouped by issue type, as each project has a set of valid issue types and each issue type has a set of valid statuses.

This operation can be accessed anonymously.

**[Permissions](#permissions) required:** *Browse Projects* [project permission](https://confluence.atlassian.com/x/yodKLg) for the project.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `projectIdOrKey` | path | string | Yes | The project ID or project key (case sensitive). |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 404 | Returned if the project is not found or the user does not have permission to view it. |

**Success Response Schema:**

Array of [IssueTypeWithStatus](../schemas/Issue/IssueTypeWithStatus.md)

## Security

- **basicAuth**
- **OAuth2**: read:jira-work

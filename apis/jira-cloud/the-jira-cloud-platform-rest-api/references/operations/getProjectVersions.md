# GET /rest/api/3/project/{projectIdOrKey}/versions

**Resource:** [Project versions](../resources/Project-versions.md)
**Get project versions**
**Operation ID:** `getProjectVersions`

Returns all versions in a project. The response is not paginated. Use [Get project versions paginated](#api-rest-api-3-project-projectIdOrKey-version-get) if you want to get the versions in a project with pagination.

This operation can be accessed anonymously.

**[Permissions](#permissions) required:** *Browse Projects* [project permission](https://confluence.atlassian.com/x/yodKLg) for the project.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `projectIdOrKey` | path | string | Yes | The project ID or project key (case sensitive). |
| `expand` | query | string | No | Use [expand](#expansion) to include additional information in the response. This parameter accepts `operations`, which returns actions that can be performed on the version. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 404 | Returned if the project is not found or the user does not have permission to view it. |

**Success Response Schema:**

Array of [Version](../schemas/Version/Version.md)

## Security

- **basicAuth**
- **OAuth2**: read:jira-work

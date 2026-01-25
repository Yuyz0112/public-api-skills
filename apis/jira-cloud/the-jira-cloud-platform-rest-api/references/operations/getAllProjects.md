# GET /rest/api/3/project

**Resource:** [Projects](../resources/Projects.md)
**Get all projects**
**Operation ID:** `getAllProjects`
⚠️ **Deprecated**

Returns all projects visible to the user. Deprecated, use [ Get projects paginated](#api-rest-api-3-project-search-get) that supports search and pagination.

This operation can be accessed anonymously.

**[Permissions](#permissions) required:** Projects are returned only where the user has *Browse Projects* or *Administer projects* [project permission](https://confluence.atlassian.com/x/yodKLg) for the project.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `expand` | query | string | No | Use [expand](#expansion) to include additional information in the response. This parameter accepts a comma-separated list. Expanded options include:

 *  `description` Returns the project description.
 *  `issueTypes` Returns all issue types associated with the project.
 *  `lead` Returns information about the project lead.
 *  `projectKeys` Returns all project keys associated with the project. |
| `recent` | query | integer (int32) | No | Returns the user's most recently accessed projects. You may specify the number of results to return up to a maximum of 20. If access is anonymous, then the recently accessed projects are based on the current HTTP session. |
| `properties` | query | string[] | No | A list of project properties to return for the project. This parameter accepts a comma-separated list. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 401 | Returned if the authentication credentials are incorrect or missing. |

**Success Response Schema:**

Array of [Project](../schemas/Project/Project.md)

## Security

- **basicAuth**
- **OAuth2**: read:jira-work

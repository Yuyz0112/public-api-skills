# GET /rest/api/3/project/{projectIdOrKey}

**Resource:** [Projects](../resources/Projects.md)
**Get project**
**Operation ID:** `getProject`

Returns the [project details](https://confluence.atlassian.com/x/ahLpNw) for a project.

This operation can be accessed anonymously.

**[Permissions](#permissions) required:** *Browse projects* [project permission](https://confluence.atlassian.com/x/yodKLg) for the project.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `projectIdOrKey` | path | string | Yes | The project ID or project key (case sensitive). |
| `expand` | query | string | No | Use [expand](#expansion) to include additional information in the response. This parameter accepts a comma-separated list. Note that the project description, issue types, and project lead are included in all responses by default. Expand options include:

 *  `description` The project description.
 *  `issueTypes` The issue types associated with the project.
 *  `lead` The project lead.
 *  `projectKeys` All project keys associated with the project.
 *  `issueTypeHierarchy` The project issue type hierarchy. |
| `properties` | query | string[] | No | A list of project properties to return for the project. This parameter accepts a comma-separated list. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if successful. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 404 | Returned if the project is not found or the user does not have permission to view it. |

**Success Response Schema:**

[Project](../schemas/Project/Project.md)

## Security

- **basicAuth**
- **OAuth2**: read:jira-work

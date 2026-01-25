# GET /rest/api/3/project/recent

**Resource:** [Projects](../resources/Projects.md)
**Get recent projects**
**Operation ID:** `getRecent`

Returns a list of up to 20 projects recently viewed by the user that are still visible to the user.

This operation can be accessed anonymously.

**[Permissions](#permissions) required:** Projects are returned only where the user has one of:

 *  *Browse Projects* [project permission](https://confluence.atlassian.com/x/yodKLg) for the project.
 *  *Administer Projects* [project permission](https://confluence.atlassian.com/x/yodKLg) for the project.
 *  *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `expand` | query | string | No | Use [expand](#expansion) to include additional information in the response. This parameter accepts a comma-separated list. Expanded options include:

 *  `description` Returns the project description.
 *  `projectKeys` Returns all project keys associated with a project.
 *  `lead` Returns information about the project lead.
 *  `issueTypes` Returns all issue types associated with the project.
 *  `url` Returns the URL associated with the project.
 *  `permissions` Returns the permissions associated with the project.
 *  `insight` EXPERIMENTAL. Returns the insight details of total issue count and last issue update time for the project.
 *  `*` Returns the project with all available expand options. |
| `properties` | query | StringList[] | No | EXPERIMENTAL. A list of project properties to return for the project. This parameter accepts a comma-separated list. Invalid property names are ignored. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 400 | Returned if the request is not valid. |
| 401 | Returned if the authentication credentials are incorrect or missing. |

**Success Response Schema:**

Array of [Project](../schemas/Project/Project.md)

## Security

- **basicAuth**
- **OAuth2**: read:jira-work

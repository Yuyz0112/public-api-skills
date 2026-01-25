# PUT /rest/api/3/project/{projectIdOrKey}

**Resource:** [Projects](../resources/Projects.md)
**Update project**
**Operation ID:** `updateProject`

Updates the [project details](https://confluence.atlassian.com/x/ahLpNw) of a project.

All parameters are optional in the body of the request. Schemes will only be updated if they are included in the request, any omitted schemes will be left unchanged.

**[Permissions](#permissions) required:** *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg). is only needed when changing the schemes or project key. Otherwise you will only need *Administer Projects* [project permission](https://confluence.atlassian.com/x/yodKLg)

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `projectIdOrKey` | path | string | Yes | The project ID or project key (case sensitive). |
| `expand` | query | string | No | Use [expand](#expansion) to include additional information in the response. This parameter accepts a comma-separated list. Note that the project description, issue types, and project lead are included in all responses by default. Expand options include:

 *  `description` The project description.
 *  `issueTypes` The issue types associated with the project.
 *  `lead` The project lead.
 *  `projectKeys` All project keys associated with the project. |

## Request Body

The project details to be updated.

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [UpdateProjectDetails](../schemas/Update/UpdateProjectDetails.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the project is updated. |
| 400 | Returned if the request is not valid. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 403 | Returned if:

 *  the user does not have the necessary permission to update project details.
 *  the permission scheme is being changed and the Jira instance is Jira Core Free or Jira Software Free. Permission schemes cannot be changed on free plans. |
| 404 | Returned if the project is not found. |

**Success Response Schema:**

[Project](../schemas/Project/Project.md)

## Security

- **basicAuth**
- **OAuth2**: manage:jira-project

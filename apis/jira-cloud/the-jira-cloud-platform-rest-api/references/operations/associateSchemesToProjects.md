# PUT /rest/api/3/issuesecurityschemes/project

**Resource:** [Issue security schemes](../resources/Issue-security-schemes.md)
**Associate security scheme to project**
**Operation ID:** `associateSchemesToProjects`

Associates an issue security scheme with a project and remaps security levels of issues to the new levels, if provided.

This operation is [asynchronous](#async). Follow the `location` link in the response to determine the status of the task and use [Get task](#api-rest-api-3-task-taskId-get) to obtain subsequent updates.

**[Permissions](#permissions) required:** *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg).

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [AssociateSecuritySchemeWithProjectDetails](../schemas/Associate/AssociateSecuritySchemeWithProjectDetails.md)

## Responses

| Status | Description |
|--------|-------------|
| 303 | Returned if the request is successful. |
| 400 | Returned if the request is invalid. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 403 | Returned if the user doesn't have the necessary permission. |
| 404 | Returned if the security scheme isn't found. |
| 409 | Returned if a task to remove the issue security level is already running. |

## Security

- **basicAuth**
- **OAuth2**: manage:jira-configuration

# POST /rest/api/3/component

**Resource:** [Project components](../resources/Project-components.md)
**Create component**
**Operation ID:** `createComponent`

Creates a component. Use components to provide containers for issues within a project. Use components to provide containers for issues within a project.

This operation can be accessed anonymously.

**[Permissions](#permissions) required:** *Administer projects* [project permission](https://confluence.atlassian.com/x/yodKLg) for the project in which the component is created or *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg).

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [ProjectComponent](../schemas/Project/ProjectComponent.md)

## Responses

| Status | Description |
|--------|-------------|
| 201 | Returned if the request is successful. |
| 400 | Returned if:

 *  the user is not found.
 *  `name` is not provided.
 *  `name` is over 255 characters in length.
 *  `projectId` is not provided.
 *  `assigneeType` is an invalid value. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 403 | Returned if the user does not have permission to manage the project containing the component or does not have permission to administer Jira. |
| 404 | Returned if the project is not found or the user does not have permission to browse the project containing the component. |

**Success Response Schema:**

[ProjectComponent](../schemas/Project/ProjectComponent.md)

## Security

- **basicAuth**
- **OAuth2**: manage:jira-project

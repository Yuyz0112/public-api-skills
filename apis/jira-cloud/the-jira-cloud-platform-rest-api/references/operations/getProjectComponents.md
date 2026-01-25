# GET /rest/api/3/project/{projectIdOrKey}/components

**Resource:** [Project components](../resources/Project-components.md)
**Get project components**
**Operation ID:** `getProjectComponents`

Returns all components in a project. See the [Get project components paginated](#api-rest-api-3-project-projectIdOrKey-component-get) resource if you want to get a full list of components with pagination.

If your project uses Compass components, this API will return a paginated list of Compass components that are linked to issues in that project.

This operation can be accessed anonymously.

**[Permissions](#permissions) required:** *Browse Projects* [project permission](https://confluence.atlassian.com/x/yodKLg) for the project.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `projectIdOrKey` | path | string | Yes | The project ID or project key (case sensitive). |
| `componentSource` | query | enum: jira, compass, auto | No | The source of the components to return. Can be `jira` (default), `compass` or `auto`. When `auto` is specified, the API will return connected Compass components if the project is opted into Compass, otherwise it will return Jira components. Defaults to `jira`. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 404 | Returned if the project is not found or the user does not have permission to view it. |

**Success Response Schema:**

Array of [ProjectComponent](../schemas/Project/ProjectComponent.md)

## Security

- **basicAuth**
- **OAuth2**: read:jira-work

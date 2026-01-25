# GET /rest/api/3/project/{projectIdOrKey}/component

**Resource:** [Project components](../resources/Project-components.md)
**Get project components paginated**
**Operation ID:** `getProjectComponentsPaginated`

Returns a [paginated](#pagination) list of all components in a project. See the [Get project components](#api-rest-api-3-project-projectIdOrKey-components-get) resource if you want to get a full list of versions without pagination.

If your project uses Compass components, this API will return a list of Compass components that are linked to issues in that project.

This operation can be accessed anonymously.

**[Permissions](#permissions) required:** *Browse Projects* [project permission](https://confluence.atlassian.com/x/yodKLg) for the project.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `projectIdOrKey` | path | string | Yes | The project ID or project key (case sensitive). |
| `startAt` | query | integer (int64) | No | The index of the first item to return in a page of results (page offset). |
| `maxResults` | query | integer (int32) | No | The maximum number of items to return per page. |
| `orderBy` | query | enum: description, -description, +description... | No | [Order](#ordering) the results by a field:

 *  `description` Sorts by the component description.
 *  `issueCount` Sorts by the count of issues associated with the component.
 *  `lead` Sorts by the user key of the component's project lead.
 *  `name` Sorts by component name. |
| `componentSource` | query | enum: jira, compass, auto | No | The source of the components to return. Can be `jira` (default), `compass` or `auto`. When `auto` is specified, the API will return connected Compass components if the project is opted into Compass, otherwise it will return Jira components. Defaults to `jira`. |
| `query` | query | string | No | Filter the results using a literal string. Components with a matching `name` or `description` are returned (case insensitive). |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 404 | Returned if the project is not found or the user does not have permission to view it. |

**Success Response Schema:**

[PageBeanComponentWithIssueCount](../schemas/Page/PageBeanComponentWithIssueCount.md)

## Security

- **basicAuth**
- **OAuth2**: read:jira-work

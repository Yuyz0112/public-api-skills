# GET /rest/api/3/component

**Resource:** [Project components](../resources/Project-components.md)
**Find components for projects**
**Operation ID:** `findComponentsForProjects`

Returns a [paginated](#pagination) list of all components in a project, including global (Compass) components when applicable.

This operation can be accessed anonymously.

**[Permissions](#permissions) required:** *Browse Projects* [project permission](https://confluence.atlassian.com/x/yodKLg) for the project.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `projectIdsOrKeys` | query | string[] | No | The project IDs and/or project keys (case sensitive). |
| `startAt` | query | integer (int64) | No | The index of the first item to return in a page of results (page offset). |
| `maxResults` | query | integer (int32) | No | The maximum number of items to return per page. |
| `orderBy` | query | enum: description, -description, +description... | No | [Order](#ordering) the results by a field:

 *  `description` Sorts by the component description.
 *  `name` Sorts by component name. |
| `query` | query | string | No | Filter the results using a literal string. Components with a matching `name` or `description` are returned (case insensitive). |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 404 | Returned if the project is not found or the user does not have permission to view it. |

**Success Response Schema:**

[PageBean2ComponentJsonBean](../schemas/Page/PageBean2ComponentJsonBean.md)

## Security

- **basicAuth**
- **OAuth2**: read:jira-work

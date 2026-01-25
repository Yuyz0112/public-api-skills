# GET /rest/api/3/priorityscheme/{schemeId}/projects

**Resource:** [Priority schemes](../resources/Priority-schemes.md)
**Get projects by priority scheme**
**Operation ID:** `getProjectsByPriorityScheme`

Returns a [paginated](#pagination) list of projects by scheme.

**[Permissions](#permissions) required:** Permission to access Jira.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `startAt` | query | string | No | The index of the first item to return in a page of results (page offset). |
| `maxResults` | query | string | No | The maximum number of items to return per page. |
| `projectId` | query | integer[] | No | The project IDs to filter by. For example, `projectId=10000&projectId=10001`. |
| `schemeId` | path | string | Yes | The priority scheme ID. |
| `query` | query | string | No | The string to query projects on by name. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 400 | Returned if the request isn't valid. |
| 401 | Returned if the authentication credentials are incorrect. |

**Success Response Schema:**

[PageBeanProject](../schemas/Page/PageBeanProject.md)

## Security

- **basicAuth**
- **OAuth2**: manage:jira-configuration

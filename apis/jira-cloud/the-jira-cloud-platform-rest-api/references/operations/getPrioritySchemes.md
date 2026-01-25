# GET /rest/api/3/priorityscheme

**Resource:** [Priority schemes](../resources/Priority-schemes.md)
**Get priority schemes**
**Operation ID:** `getPrioritySchemes`

Returns a [paginated](#pagination) list of priority schemes.

**[Permissions](#permissions) required:** Permission to access Jira.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `startAt` | query | string | No | The index of the first item to return in a page of results (page offset). |
| `maxResults` | query | string | No | The maximum number of items to return per page. |
| `priorityId` | query | integer[] | No | A set of priority IDs to filter by. To include multiple IDs, provide an ampersand-separated list. For example, `priorityId=10000&priorityId=10001`. |
| `schemeId` | query | integer[] | No | A set of priority scheme IDs. To include multiple IDs, provide an ampersand-separated list. For example, `schemeId=10000&schemeId=10001`. |
| `schemeName` | query | string | No | The name of scheme to search for. |
| `onlyDefault` | query | boolean | No | Whether only the default priority is returned. |
| `orderBy` | query | enum: name, +name, -name | No | The ordering to return the priority schemes by. |
| `expand` | query | string | No | A comma separated list of additional information to return. "priorities" will return priorities associated with the priority scheme. "projects" will return projects associated with the priority scheme. `expand=priorities,projects`. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 400 | Returned if the request isn't valid. |
| 401 | Returned if the authentication credentials are incorrect. |

**Success Response Schema:**

[PageBeanPrioritySchemeWithPaginatedPrioritiesAndProjects](../schemas/Page/PageBeanPrioritySchemeWithPaginatedPrioritiesAndProjects.md)

## Security

- **basicAuth**
- **OAuth2**: manage:jira-configuration

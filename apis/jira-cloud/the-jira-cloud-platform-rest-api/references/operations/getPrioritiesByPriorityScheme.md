# GET /rest/api/3/priorityscheme/{schemeId}/priorities

**Resource:** [Priority schemes](../resources/Priority-schemes.md)
**Get priorities by priority scheme**
**Operation ID:** `getPrioritiesByPriorityScheme`

Returns a [paginated](#pagination) list of priorities by scheme.

**[Permissions](#permissions) required:** Permission to access Jira.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `startAt` | query | string | No | The index of the first item to return in a page of results (page offset). |
| `maxResults` | query | string | No | The maximum number of items to return per page. |
| `schemeId` | path | string | Yes | The priority scheme ID. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 400 | Returned if the request isn't valid. |
| 401 | Returned if the authentication credentials are incorrect. |

**Success Response Schema:**

[PageBeanPriorityWithSequence](../schemas/Page/PageBeanPriorityWithSequence.md)

## Security

- **basicAuth**
- **OAuth2**: manage:jira-configuration

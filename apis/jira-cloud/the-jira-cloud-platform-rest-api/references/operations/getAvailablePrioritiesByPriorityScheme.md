# GET /rest/api/3/priorityscheme/priorities/available

**Resource:** [Priority schemes](../resources/Priority-schemes.md)
**Get available priorities by priority scheme**
**Operation ID:** `getAvailablePrioritiesByPriorityScheme`

Returns a [paginated](#pagination) list of priorities available for adding to a priority scheme.

**[Permissions](#permissions) required:** Permission to access Jira.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `startAt` | query | string | No | The index of the first item to return in a page of results (page offset). |
| `maxResults` | query | string | No | The maximum number of items to return per page. |
| `query` | query | string | No | The string to query priorities on by name. |
| `schemeId` | query | string | Yes | The priority scheme ID. |
| `exclude` | query | string[] | No | A list of priority IDs to exclude from the results. |

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

# GET /rest/api/3/priority/search

**Resource:** [Issue priorities](../resources/Issue-priorities.md)
**Search priorities**
**Operation ID:** `searchPriorities`
⚠️ **Deprecated**

Returns a [paginated](#pagination) list of priorities. The list can contain all priorities or a subset determined by any combination of these criteria:

 *  a list of priority IDs. Any invalid priority IDs are ignored.
 *  a list of project IDs. Only priorities that are available in these projects will be returned. Any invalid project IDs are ignored.
 *  whether the field configuration is a default. This returns priorities from company-managed (classic) projects only, as there is no concept of default priorities in team-managed projects.

**[Permissions](#permissions) required:** Permission to access Jira.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `startAt` | query | string | No | The index of the first item to return in a page of results (page offset). |
| `maxResults` | query | string | No | The maximum number of items to return per page. |
| `id` | query | string[] | No | The list of priority IDs. To include multiple IDs, provide an ampersand-separated list. For example, `id=2&id=3`. |
| `projectId` | query | string[] | No | The list of projects IDs. To include multiple IDs, provide an ampersand-separated list. For example, `projectId=10010&projectId=10111`. |
| `priorityName` | query | string | No | The name of priority to search for. |
| `onlyDefault` | query | boolean | No | Whether only the default priority is returned. |
| `expand` | query | string | No | Use `schemes` to return the associated priority schemes for each priority. Limited to returning first 15 priority schemes per priority. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 401 | Returned if the authentication credentials are incorrect or missing. |

**Success Response Schema:**

[PageBeanPriority](../schemas/Page/PageBeanPriority.md)

## Security

- **basicAuth**
- **OAuth2**: manage:jira-configuration

# GET /rest/api/3/resolution/search

**Resource:** [Issue resolutions](../resources/Issue-resolutions.md)
**Search resolutions**
**Operation ID:** `searchResolutions`

Returns a [paginated](#pagination) list of resolutions. The list can contain all resolutions or a subset determined by any combination of these criteria:

 *  a list of resolutions IDs.
 *  whether the field configuration is a default. This returns resolutions from company-managed (classic) projects only, as there is no concept of default resolutions in team-managed projects.

**[Permissions](#permissions) required:** Permission to access Jira.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `startAt` | query | string | No | The index of the first item to return in a page of results (page offset). |
| `maxResults` | query | string | No | The maximum number of items to return per page. |
| `id` | query | string[] | No | The list of resolutions IDs to be filtered out |
| `onlyDefault` | query | boolean | No | When set to true, return default only, when IDs provided, if none of them is default, return empty page. Default value is false |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 401 | Returned if the authentication credentials are incorrect or missing. |

**Success Response Schema:**

[PageBeanResolutionJsonBean](../schemas/Page/PageBeanResolutionJsonBean.md)

## Security

- **basicAuth**
- **OAuth2**: read:jira-work

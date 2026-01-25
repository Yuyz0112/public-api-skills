# Filter

Details about a filter.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `approximateLastUsed` | string (date-time) | No | \[Experimental\] Approximate last used time. Returns the date and time when the filter was last used. Returns `null` if the filter hasn't been used after tracking was enabled. For performance reasons, timestamps aren't updated in real time and therefore may not be exactly accurate. |
| `description` | string | No | A description of the filter. |
| `editPermissions` | SharePermission[] | No | The groups and projects that can edit the filter. |
| `favourite` | boolean | No | Whether the filter is selected as a favorite. |
| `favouritedCount` | integer (int64) | No | The count of how many users have selected this filter as a favorite, including the filter owner. |
| `id` | string | No | The unique identifier for the filter. |
| `jql` | string | No | The JQL query for the filter. For example, *project = SSP AND issuetype = Bug*. |
| `name` | string | Yes | The name of the filter. Must be unique. |
| `owner` | any | No | The user who owns the filter. This is defaulted to the creator of the filter, however Jira administrators can change the owner of a shared filter in the admin settings. |
| `searchUrl` | string (uri) | No | A URL to view the filter results in Jira, using the [Search for issues using JQL](#api-rest-api-3-filter-search-get) operation with the filter's JQL string to return the filter results. For example, *https://your-domain.atlassian.net/rest/api/3/search?jql=project+%3D+SSP+AND+issuetype+%3D+Bug*. |
| `self` | string (uri) | No | The URL of the filter. |
| `sharePermissions` | SharePermission[] | No | The groups and projects that the filter is shared with. |
| `sharedUsers` | any | No | A paginated list of the users that the filter is shared with. This includes users that are members of the groups or can browse the projects that the filter is shared with. |
| `subscriptions` | any | No | A paginated list of the users that are subscribed to the filter. |
| `viewUrl` | string (uri) | No | A URL to view the filter results in Jira, using the ID of the filter. For example, *https://your-domain.atlassian.net/issues/?filter=10100*. |


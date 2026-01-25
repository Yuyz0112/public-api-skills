# GET /rest/api/3/dashboard/search

**Resource:** [Dashboards](../resources/Dashboards.md)
**Search for dashboards**
**Operation ID:** `getDashboardsPaginated`

Returns a [paginated](#pagination) list of dashboards. This operation is similar to [Get dashboards](#api-rest-api-3-dashboard-get) except that the results can be refined to include dashboards that have specific attributes. For example, dashboards with a particular name. When multiple attributes are specified only filters matching all attributes are returned.

This operation can be accessed anonymously.

**[Permissions](#permissions) required:** The following dashboards that match the query parameters are returned:

 *  Dashboards owned by the user. Not returned for anonymous users.
 *  Dashboards shared with a group that the user is a member of. Not returned for anonymous users.
 *  Dashboards shared with a private project that the user can browse. Not returned for anonymous users.
 *  Dashboards shared with a public project.
 *  Dashboards shared with the public.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `dashboardName` | query | string | No | String used to perform a case-insensitive partial match with `name`. |
| `accountId` | query | string | No | User account ID used to return dashboards with the matching `owner.accountId`. This parameter cannot be used with the `owner` parameter. |
| `owner` | query | string | No | This parameter is deprecated because of privacy changes. Use `accountId` instead. See the [migration guide](https://developer.atlassian.com/cloud/jira/platform/deprecation-notice-user-privacy-api-migration-guide/) for details. User name used to return dashboards with the matching `owner.name`. This parameter cannot be used with the `accountId` parameter. |
| `groupname` | query | string | No | As a group's name can change, use of `groupId` is recommended. Group name used to return dashboards that are shared with a group that matches `sharePermissions.group.name`. This parameter cannot be used with the `groupId` parameter. |
| `groupId` | query | string | No | Group ID used to return dashboards that are shared with a group that matches `sharePermissions.group.groupId`. This parameter cannot be used with the `groupname` parameter. |
| `projectId` | query | integer (int64) | No | Project ID used to returns dashboards that are shared with a project that matches `sharePermissions.project.id`. |
| `orderBy` | query | enum: description, -description, +description... | No | [Order](#ordering) the results by a field:

 *  `description` Sorts by dashboard description. Note that this sort works independently of whether the expand to display the description field is in use.
 *  `favourite_count` Sorts by dashboard popularity.
 *  `id` Sorts by dashboard ID.
 *  `is_favourite` Sorts by whether the dashboard is marked as a favorite.
 *  `name` Sorts by dashboard name.
 *  `owner` Sorts by dashboard owner name. |
| `startAt` | query | integer (int64) | No | The index of the first item to return in a page of results (page offset). |
| `maxResults` | query | integer (int32) | No | The maximum number of items to return per page. |
| `status` | query | enum: active, archived, deleted | No | The status to filter by. It may be active, archived or deleted. |
| `expand` | query | string | No | Use [expand](#expansion) to include additional information about dashboard in the response. This parameter accepts a comma-separated list. Expand options include:

 *  `description` Returns the description of the dashboard.
 *  `owner` Returns the owner of the dashboard.
 *  `viewUrl` Returns the URL that is used to view the dashboard.
 *  `favourite` Returns `isFavourite`, an indicator of whether the user has set the dashboard as a favorite.
 *  `favouritedCount` Returns `popularity`, a count of how many users have set this dashboard as a favorite.
 *  `sharePermissions` Returns details of the share permissions defined for the dashboard.
 *  `editPermissions` Returns details of the edit permissions defined for the dashboard.
 *  `isWritable` Returns whether the current user has permission to edit the dashboard. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 400 | Returned if:

 *  `orderBy` is invalid.
 *  `expand` includes an invalid value.
 *  `accountId` and `owner` are provided.
 *  `groupname` and `groupId` are provided. |
| 401 | 401 response |

**Success Response Schema:**

[PageBeanDashboard](../schemas/Page/PageBeanDashboard.md)

## Security

- **basicAuth**
- **OAuth2**: read:jira-work

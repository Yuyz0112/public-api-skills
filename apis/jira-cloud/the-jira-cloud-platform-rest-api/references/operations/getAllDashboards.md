# GET /rest/api/3/dashboard

**Resource:** [Dashboards](../resources/Dashboards.md)
**Get all dashboards**
**Operation ID:** `getAllDashboards`

Returns a list of dashboards owned by or shared with the user. The list may be filtered to include only favorite or owned dashboards.

This operation can be accessed anonymously.

**[Permissions](#permissions) required:** None.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `filter` | query | enum: my, favourite | No | The filter applied to the list of dashboards. Valid values are:

 *  `favourite` Returns dashboards the user has marked as favorite.
 *  `my` Returns dashboards owned by the user. |
| `startAt` | query | integer (int32) | No | The index of the first item to return in a page of results (page offset). |
| `maxResults` | query | integer (int32) | No | The maximum number of items to return per page. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 400 | Returned if the request is invalid. |
| 401 | Returned if the authentication credentials are incorrect or missing. |

**Success Response Schema:**

[PageOfDashboards](../schemas/Page/PageOfDashboards.md)

## Security

- **basicAuth**
- **OAuth2**: read:jira-work

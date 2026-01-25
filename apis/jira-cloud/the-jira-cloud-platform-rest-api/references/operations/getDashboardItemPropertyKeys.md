# GET /rest/api/3/dashboard/{dashboardId}/items/{itemId}/properties

**Resource:** [Dashboards](../resources/Dashboards.md)
**Get dashboard item property keys**
**Operation ID:** `getDashboardItemPropertyKeys`

Returns the keys of all properties for a dashboard item.

This operation can be accessed anonymously.

**[Permissions](#permissions) required:** The user must have read permission of the dashboard or have the dashboard shared with them.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `dashboardId` | path | string | Yes | The ID of the dashboard. |
| `itemId` | path | string | Yes | The ID of the dashboard item. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 404 | Returned if the dashboard or dashboard item is not found, or the dashboard is not owned by or shared with the user. |

**Success Response Schema:**

[PropertyKeys](../schemas/Property/PropertyKeys.md)

## Security

- **basicAuth**
- **OAuth2**: read:jira-work

# DELETE /rest/api/3/dashboard/{dashboardId}/items/{itemId}/properties/{propertyKey}

**Resource:** [Dashboards](../resources/Dashboards.md)
**Delete dashboard item property**
**Operation ID:** `deleteDashboardItemProperty`

Deletes a dashboard item property.

This operation can be accessed anonymously.

**[Permissions](#permissions) required:** The user must have edit permission of the dashboard.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `dashboardId` | path | string | Yes | The ID of the dashboard. |
| `itemId` | path | string | Yes | The ID of the dashboard item. |
| `propertyKey` | path | string | Yes | The key of the dashboard item property. |

## Responses

| Status | Description |
|--------|-------------|
| 204 | Returned if the dashboard item property is deleted. |
| 400 | Returned if the dashboard or dashboard item ID is invalid. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 403 | Returned if the user is not the owner of the dashboard. |
| 404 | Returned if the dashboard item is not found or the dashboard is not shared with the user. |

## Security

- **basicAuth**
- **OAuth2**: write:jira-work

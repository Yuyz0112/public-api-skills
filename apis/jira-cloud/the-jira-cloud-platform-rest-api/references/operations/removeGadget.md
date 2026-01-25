# DELETE /rest/api/3/dashboard/{dashboardId}/gadget/{gadgetId}

**Resource:** [Dashboards](../resources/Dashboards.md)
**Remove gadget from dashboard**
**Operation ID:** `removeGadget`

Removes a dashboard gadget from a dashboard.

When a gadget is removed from a dashboard, other gadgets in the same column are moved up to fill the emptied position.

**[Permissions](#permissions) required:** None.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `dashboardId` | path | integer (int64) | Yes | The ID of the dashboard. |
| `gadgetId` | path | integer (int64) | Yes | The ID of the gadget. |

## Responses

| Status | Description |
|--------|-------------|
| 204 | Returned if the request is successful. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 404 | Returned if the gadget or the dashboard is not found. |

## Security

- **basicAuth**
- **OAuth2**: write:jira-work

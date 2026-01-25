# PUT /rest/api/3/dashboard/{dashboardId}/gadget/{gadgetId}

**Resource:** [Dashboards](../resources/Dashboards.md)
**Update gadget on dashboard**
**Operation ID:** `updateGadget`

Changes the title, position, and color of the gadget on a dashboard.

**[Permissions](#permissions) required:** None.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `dashboardId` | path | integer (int64) | Yes | The ID of the dashboard. |
| `gadgetId` | path | integer (int64) | Yes | The ID of the gadget. |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [DashboardGadgetUpdateRequest](../schemas/Dashboard/DashboardGadgetUpdateRequest.md)

## Responses

| Status | Description |
|--------|-------------|
| 204 | Returned if the request is successful. |
| 400 | Returned if the request is invalid. |
| 401 | Returned if the authentication credentials are incorrect. |
| 404 | Returned if the gadget or the dashboard is not found. |

## Security

- **basicAuth**
- **OAuth2**: write:jira-work

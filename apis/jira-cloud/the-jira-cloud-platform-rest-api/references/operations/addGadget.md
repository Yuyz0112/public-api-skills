# POST /rest/api/3/dashboard/{dashboardId}/gadget

**Resource:** [Dashboards](../resources/Dashboards.md)
**Add gadget to dashboard**
**Operation ID:** `addGadget`

Adds a gadget to a dashboard.

**[Permissions](#permissions) required:** None.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `dashboardId` | path | integer (int64) | Yes | The ID of the dashboard. |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [DashboardGadgetSettings](../schemas/Dashboard/DashboardGadgetSettings.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 400 | Returned if the request is invalid. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 404 | Returned if the dashboard is not found. |

**Success Response Schema:**

[DashboardGadget](../schemas/Dashboard/DashboardGadget.md)

## Security

- **basicAuth**
- **OAuth2**: write:jira-work, read:jira-work

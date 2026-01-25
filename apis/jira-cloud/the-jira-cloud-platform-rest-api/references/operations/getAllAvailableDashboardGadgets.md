# GET /rest/api/3/dashboard/gadgets

**Resource:** [Dashboards](../resources/Dashboards.md)
**Get available gadgets**
**Operation ID:** `getAllAvailableDashboardGadgets`

Gets a list of all available gadgets that can be added to all dashboards.

**[Permissions](#permissions) required:** None.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 400 | 400 response |
| 401 | Returned if the authentication credentials are incorrect or missing. |

**Success Response Schema:**

[AvailableDashboardGadgetsResponse](../schemas/Available/AvailableDashboardGadgetsResponse.md)

## Security

- **basicAuth**
- **OAuth2**: read:jira-work

# GET /rest/api/3/dashboard/{dashboardId}/gadget

**Resource:** [Dashboards](../resources/Dashboards.md)
**Get gadgets**
**Operation ID:** `getAllGadgets`

Returns a list of dashboard gadgets on a dashboard.

This operation returns:

 *  Gadgets from a list of IDs, when `id` is set.
 *  Gadgets with a module key, when `moduleKey` is set.
 *  Gadgets from a list of URIs, when `uri` is set.
 *  All gadgets, when no other parameters are set.

This operation can be accessed anonymously.

**[Permissions](#permissions) required:** None.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `dashboardId` | path | integer (int64) | Yes | The ID of the dashboard. |
| `moduleKey` | query | string[] | No | The list of gadgets module keys. To include multiple module keys, separate module keys with ampersand: `moduleKey=key:one&moduleKey=key:two`. |
| `uri` | query | string[] | No | The list of gadgets URIs. To include multiple URIs, separate URIs with ampersand: `uri=/rest/example/uri/1&uri=/rest/example/uri/2`. |
| `gadgetId` | query | integer[] | No | The list of gadgets IDs. To include multiple IDs, separate IDs with ampersand: `gadgetId=10000&gadgetId=10001`. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 401 | Returned if the authentication credentials are incorrect. |
| 404 | Returned if the dashboard is not found. |

**Success Response Schema:**

[DashboardGadgetResponse](../schemas/Dashboard/DashboardGadgetResponse.md)

## Security

- **basicAuth**
- **OAuth2**: read:jira-work

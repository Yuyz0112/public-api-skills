# DELETE /user/load_balancers/monitors/{monitor_id}

**Resource:** [Load Balancer Monitors](../resources/Load-Balancer-Monitors.md)
**Delete Monitor**
**Operation ID:** `load-balancer-monitors-delete-monitor`

Delete a configured monitor.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `monitor_id` | path | load-balancing_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Delete Monitor response. |
| 4XX | Delete Monitor response failure. |

**Success Response Schema:**

[load-balancing_id_response](../schemas/load-balancing/load-balancing-id-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**

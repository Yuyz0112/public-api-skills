# PUT /user/load_balancers/monitors/{monitor_id}

**Resource:** [Load Balancer Monitors](../resources/Load-Balancer-Monitors.md)
**Update Monitor**
**Operation ID:** `load-balancer-monitors-update-monitor`

Modify a configured monitor.

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
| 200 | Update Monitor response. |
| 4XX | Update Monitor response failure. |

**Success Response Schema:**

[load-balancing_monitor-response-single](../schemas/load-balancing/load-balancing-monitor-response-single.md)

## Security

- **api_email**
- **api_key**
- **api_token**

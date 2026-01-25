# GET /user/load_balancers/monitors/{monitor_id}

**Resource:** [Load Balancer Monitors](../resources/Load-Balancer-Monitors.md)
**Monitor Details**
**Operation ID:** `load-balancer-monitors-monitor-details`

List a single configured monitor for a user.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `monitor_id` | path | load-balancing_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Monitor Details response. |
| 4XX | Monitor Details response failure. |

**Success Response Schema:**

[load-balancing_monitor-response-single](../schemas/load-balancing/load-balancing-monitor-response-single.md)

## Security

- **api_email**
- **api_key**
- **api_token**

# GET /user/load_balancers/monitors/{monitor_id}/references

**Resource:** [Load Balancer Monitors](../resources/Load-Balancer-Monitors.md)
**List Monitor References**
**Operation ID:** `load-balancer-monitors-list-monitor-references`

Get the list of resources that reference the provided monitor.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `monitor_id` | path | load-balancing_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List Monitor References response. |
| 4XX | List Monitor References response failure. |

**Success Response Schema:**

[load-balancing_monitor-references-response](../schemas/load-balancing/load-balancing-monitor-references-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**

# POST /user/load_balancers/monitors

**Resource:** [Load Balancer Monitors](../resources/Load-Balancer-Monitors.md)
**Create Monitor**
**Operation ID:** `load-balancer-monitors-create-monitor`

Create a configured monitor.

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Create Monitor response. |
| 4XX | Create Monitor response failure. |

**Success Response Schema:**

[load-balancing_monitor-response-single](../schemas/load-balancing/load-balancing-monitor-response-single.md)

## Security

- **api_email**
- **api_key**
- **api_token**

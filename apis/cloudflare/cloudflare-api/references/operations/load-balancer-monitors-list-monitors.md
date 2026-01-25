# GET /user/load_balancers/monitors

**Resource:** [Load Balancer Monitors](../resources/Load-Balancer-Monitors.md)
**List Monitors**
**Operation ID:** `load-balancer-monitors-list-monitors`

List configured monitors for a user.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful list monitors response. |
| 4XX | Failed list monitors response. |

**Success Response Schema:**

[load-balancing_monitor-response-collection](../schemas/load-balancing/load-balancing-monitor-response-collection.md)

## Security

- **api_email**
- **api_key**
- **api_token**

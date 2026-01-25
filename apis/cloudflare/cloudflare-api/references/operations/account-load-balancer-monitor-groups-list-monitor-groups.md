# GET /accounts/{account_id}/load_balancers/monitor_groups

**Resource:** [Account Load Balancer Monitor Groups](../resources/Account-Load-Balancer-Monitor-Groups.md)
**List Monitor Groups**
**Operation ID:** `account-load-balancer-monitor-groups-list-monitor-groups`

List configured monitor groups.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | load-balancing_components-schemas-identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List Monitor Groups response |
| 4XX | List Monitor Groups response failure |

**Success Response Schema:**

[load-balancing_monitor-group-response-collection](../schemas/load-balancing/load-balancing-monitor-group-response-collection.md)

## Security

- **api_email**
- **api_key**
- **api_token**

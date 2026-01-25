# GET /accounts/{account_id}/load_balancers/monitor_groups/{monitor_group_id}

**Resource:** [Account Load Balancer Monitor Groups](../resources/Account-Load-Balancer-Monitor-Groups.md)
**Monitor Group Details**
**Operation ID:** `account-load-balancer-monitor-groups-monitor-group-details`

Fetch a single configured monitor group.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `monitor_group_id` | path | load-balancing_schemas-identifier | Yes |  |
| `account_id` | path | load-balancing_components-schemas-identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Monitor Group Details response |
| 4XX | Monitor Group Details response failure |

**Success Response Schema:**

[load-balancing_monitor-group-single-response](../schemas/load-balancing/load-balancing-monitor-group-single-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**

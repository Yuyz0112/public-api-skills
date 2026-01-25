# DELETE /accounts/{account_id}/load_balancers/monitor_groups/{monitor_group_id}

**Resource:** [Account Load Balancer Monitor Groups](../resources/Account-Load-Balancer-Monitor-Groups.md)
**Delete Monitor Group**
**Operation ID:** `account-load-balancer-monitor-groups-delete-monitor-group`

Delete a configured monitor group.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `monitor_group_id` | path | load-balancing_schemas-identifier | Yes |  |
| `account_id` | path | load-balancing_components-schemas-identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Delete Monitor Group response |
| 412 | Precondition Failed - Monitor group is in use by one or more pools |
| 4XX | Delete Monitor Group response failure |

**Success Response Schema:**

[load-balancing_monitor-group-single-response](../schemas/load-balancing/load-balancing-monitor-group-single-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**

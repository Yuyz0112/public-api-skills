# GET /accounts/{account_id}/load_balancers/monitor_groups/{monitor_group_id}/references

**Resource:** [Account Load Balancer Monitor Groups](../resources/Account-Load-Balancer-Monitor-Groups.md)
**List Monitor Group References**
**Operation ID:** `account-load-balancer-monitor-groups-list-monitor-group-references`

Get the list of resources that reference the provided monitor group.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `monitor_group_id` | path | load-balancing_identifier | Yes |  |
| `account_id` | path | load-balancing_components-schemas-identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List Monitor Group References response. |
| 4XX | List Monitor Group References response failure. |

**Success Response Schema:**

[load-balancing_monitor-group-references-response](../schemas/load-balancing/load-balancing-monitor-group-references-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**

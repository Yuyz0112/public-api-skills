# PUT /accounts/{account_id}/load_balancers/monitor_groups/{monitor_group_id}

**Resource:** [Account Load Balancer Monitor Groups](../resources/Account-Load-Balancer-Monitor-Groups.md)
**Update Monitor Group**
**Operation ID:** `account-load-balancer-monitor-groups-update-monitor-group`

Modify a configured monitor group.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `monitor_group_id` | path | load-balancing_schemas-identifier | Yes |  |
| `account_id` | path | load-balancing_components-schemas-identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [load-balancing_monitor-group](../schemas/load-balancing/load-balancing-monitor-group.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Update Monitor Group response |
| 412 | Precondition Failed - Referenced monitor does not exist |
| 4XX | Update Monitor Group response failure |

**Success Response Schema:**

[load-balancing_monitor-group-single-response](../schemas/load-balancing/load-balancing-monitor-group-single-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**

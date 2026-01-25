# POST /accounts/{account_id}/load_balancers/monitor_groups

**Resource:** [Account Load Balancer Monitor Groups](../resources/Account-Load-Balancer-Monitor-Groups.md)
**Create Monitor Group**
**Operation ID:** `account-load-balancer-monitor-groups-create-monitor-group`

Create a new monitor group.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | load-balancing_components-schemas-identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [load-balancing_monitor-group](../schemas/load-balancing/load-balancing-monitor-group.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Create Monitor Group response |
| 412 | Precondition Failed - Referenced monitor does not exist |
| 4XX | Create Monitor Group response failure |

**Success Response Schema:**

[load-balancing_monitor-group-single-response](../schemas/load-balancing/load-balancing-monitor-group-single-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**

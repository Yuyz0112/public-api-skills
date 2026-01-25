# PUT /accounts/{account_id}/load_balancers/monitors/{monitor_id}

**Resource:** [Account Load Balancer Monitors](../resources/Account-Load-Balancer-Monitors.md)
**Update Monitor**
**Operation ID:** `account-load-balancer-monitors-update-monitor`

Modify a configured monitor.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `monitor_id` | path | load-balancing_identifier | Yes |  |
| `account_id` | path | load-balancing_components-schemas-identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Update Monitor response. |
| 4XX | Update Monitor response failure. |

**Success Response Schema:**

[load-balancing_monitor-response-single](../schemas/load-balancing/load-balancing-monitor-response-single.md)

## Security

- **api_email**
- **api_key**
- **api_token**

# PATCH /accounts/{account_id}/load_balancers/monitors/{monitor_id}

**Resource:** [Account Load Balancer Monitors](../resources/Account-Load-Balancer-Monitors.md)
**Patch Monitor**
**Operation ID:** `account-load-balancer-monitors-patch-monitor`

Apply changes to an existing monitor, overwriting the supplied properties.

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
| 200 | Patch Monitor response. |
| 4XX | Patch Monitor response failure. |

**Success Response Schema:**

[load-balancing_monitor-response-single](../schemas/load-balancing/load-balancing-monitor-response-single.md)

## Security

- **api_email**
- **api_key**
- **api_token**

# POST /accounts/{account_id}/load_balancers/monitors

**Resource:** [Account Load Balancer Monitors](../resources/Account-Load-Balancer-Monitors.md)
**Create Monitor**
**Operation ID:** `account-load-balancer-monitors-create-monitor`

Create a configured monitor.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | load-balancing_components-schemas-identifier | Yes |  |

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

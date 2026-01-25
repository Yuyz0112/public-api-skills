# GET /accounts/{account_id}/load_balancers/monitors

**Resource:** [Account Load Balancer Monitors](../resources/Account-Load-Balancer-Monitors.md)
**List Monitors**
**Operation ID:** `account-load-balancer-monitors-list-monitors`

List configured monitors for an account.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | load-balancing_components-schemas-identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List Monitors response. |
| 4XX | List Monitors response failure. |

**Success Response Schema:**

[load-balancing_monitor-response-collection](../schemas/load-balancing/load-balancing-monitor-response-collection.md)

## Security

- **api_email**
- **api_key**
- **api_token**

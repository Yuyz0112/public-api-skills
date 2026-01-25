# GET /accounts/{account_id}/load_balancers/pools/{pool_id}/health

**Resource:** [Account Load Balancer Pools](../resources/Account-Load-Balancer-Pools.md)
**Pool Health Details**
**Operation ID:** `account-load-balancer-pools-pool-health-details`

Fetch the latest pool health status for a single pool.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `pool_id` | path | load-balancing_schemas-identifier | Yes |  |
| `account_id` | path | load-balancing_components-schemas-identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Pool Health Details response. |
| 4XX | Pool Health Details response failure. |

**Success Response Schema:**

[load-balancing_health_details](../schemas/load-balancing/load-balancing-health-details.md)

## Security

- **api_email**
- **api_key**
- **api_token**

# GET /accounts/{account_id}/load_balancers/pools/{pool_id}

**Resource:** [Account Load Balancer Pools](../resources/Account-Load-Balancer-Pools.md)
**Pool Details**
**Operation ID:** `account-load-balancer-pools-pool-details`

Fetch a single configured pool.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `pool_id` | path | load-balancing_schemas-identifier | Yes |  |
| `account_id` | path | load-balancing_components-schemas-identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Pool Details response. |
| 4XX | Pool Details response failure. |

**Success Response Schema:**

[load-balancing_schemas-single_response](../schemas/load-balancing/load-balancing-schemas-single-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**

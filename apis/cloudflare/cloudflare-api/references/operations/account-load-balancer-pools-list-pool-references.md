# GET /accounts/{account_id}/load_balancers/pools/{pool_id}/references

**Resource:** [Account Load Balancer Pools](../resources/Account-Load-Balancer-Pools.md)
**List Pool References**
**Operation ID:** `account-load-balancer-pools-list-pool-references`

Get the list of resources that reference the provided pool.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `pool_id` | path | load-balancing_schemas-identifier | Yes |  |
| `account_id` | path | load-balancing_components-schemas-identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List Pool References response. |
| 4XX | List Pool References response failure. |

**Success Response Schema:**

[load-balancing_pools-references-response](../schemas/load-balancing/load-balancing-pools-references-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**

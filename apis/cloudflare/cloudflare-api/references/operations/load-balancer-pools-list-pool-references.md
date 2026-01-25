# GET /user/load_balancers/pools/{pool_id}/references

**Resource:** [Load Balancer Pools](../resources/Load-Balancer-Pools.md)
**List Pool References**
**Operation ID:** `load-balancer-pools-list-pool-references`

Get the list of resources that reference the provided pool.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `pool_id` | path | load-balancing_schemas-identifier | Yes |  |

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

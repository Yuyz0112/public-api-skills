# POST /user/load_balancers/pools

**Resource:** [Load Balancer Pools](../resources/Load-Balancer-Pools.md)
**Create Pool**
**Operation ID:** `load-balancer-pools-create-pool`

Create a new pool.

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Create Pool response. |
| 4XX | Create Pool response failure. |

**Success Response Schema:**

[load-balancing_schemas-single_response](../schemas/load-balancing/load-balancing-schemas-single-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**

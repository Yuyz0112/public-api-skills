# PUT /user/load_balancers/pools/{pool_id}

**Resource:** [Load Balancer Pools](../resources/Load-Balancer-Pools.md)
**Update Pool**
**Operation ID:** `load-balancer-pools-update-pool`

Modify a configured pool.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `pool_id` | path | load-balancing_schemas-identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Update Pool response. |
| 4XX | Update Pool response failure. |

**Success Response Schema:**

[load-balancing_schemas-single_response](../schemas/load-balancing/load-balancing-schemas-single-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**

# DELETE /user/load_balancers/pools/{pool_id}

**Resource:** [Load Balancer Pools](../resources/Load-Balancer-Pools.md)
**Delete Pool**
**Operation ID:** `load-balancer-pools-delete-pool`

Delete a configured pool.

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
| 200 | Delete Pool response. |
| 4XX | Delete Pool response failure. |

**Success Response Schema:**

[load-balancing_schemas-id_response](../schemas/load-balancing/load-balancing-schemas-id-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**

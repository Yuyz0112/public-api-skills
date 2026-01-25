# PATCH /user/load_balancers/pools/{pool_id}

**Resource:** [Load Balancer Pools](../resources/Load-Balancer-Pools.md)
**Patch Pool**
**Operation ID:** `load-balancer-pools-patch-pool`

Apply changes to an existing pool, overwriting the supplied properties.

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
| 200 | Patch Pool response. |
| 4XX | Patch Pool response failure. |

**Success Response Schema:**

[load-balancing_schemas-single_response](../schemas/load-balancing/load-balancing-schemas-single-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**

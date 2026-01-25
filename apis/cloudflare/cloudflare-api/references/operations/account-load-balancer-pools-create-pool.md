# POST /accounts/{account_id}/load_balancers/pools

**Resource:** [Account Load Balancer Pools](../resources/Account-Load-Balancer-Pools.md)
**Create Pool**
**Operation ID:** `account-load-balancer-pools-create-pool`

Create a new pool.

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
| 200 | Create Pool response. |
| 4XX | Create Pool response failure. |

**Success Response Schema:**

[load-balancing_schemas-single_response](../schemas/load-balancing/load-balancing-schemas-single-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**

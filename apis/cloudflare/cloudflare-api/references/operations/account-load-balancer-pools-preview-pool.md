# POST /accounts/{account_id}/load_balancers/pools/{pool_id}/preview

**Resource:** [Account Load Balancer Pools](../resources/Account-Load-Balancer-Pools.md)
**Preview Pool**
**Operation ID:** `account-load-balancer-pools-preview-pool`

Preview pool health using provided monitor details. The returned preview_id can be used in the preview endpoint to retrieve the results.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `pool_id` | path | load-balancing_schemas-identifier | Yes |  |
| `account_id` | path | load-balancing_components-schemas-identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Preview Pool response. |
| 4XX | Preview Pool response failure. |

**Success Response Schema:**

[load-balancing_preview_response](../schemas/load-balancing/load-balancing-preview-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**

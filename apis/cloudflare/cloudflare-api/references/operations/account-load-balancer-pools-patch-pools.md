# PATCH /accounts/{account_id}/load_balancers/pools

**Resource:** [Account Load Balancer Pools](../resources/Account-Load-Balancer-Pools.md)
**Patch Pools**
**Operation ID:** `account-load-balancer-pools-patch-pools`

Apply changes to a number of existing pools, overwriting the supplied properties. Pools are ordered by ascending `name`. Returns the list of affected pools. Supports the standard pagination query parameters, either `limit`/`offset` or `per_page`/`page`.

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
| 200 | Patch Pools response. |
| 4XX | Patch Pools response failure. |

**Success Response Schema:**

[load-balancing_schemas-response_collection](../schemas/load-balancing/load-balancing-schemas-response-collection.md)

## Security

- **api_email**
- **api_key**
- **api_token**

# PATCH /user/load_balancers/pools

**Resource:** [Load Balancer Pools](../resources/Load-Balancer-Pools.md)
**Patch Pools**
**Operation ID:** `load-balancer-pools-patch-pools`

Apply changes to a number of existing pools, overwriting the supplied properties. Pools are ordered by ascending `name`. Returns the list of affected pools. Supports the standard pagination query parameters, either `limit`/`offset` or `per_page`/`page`.

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

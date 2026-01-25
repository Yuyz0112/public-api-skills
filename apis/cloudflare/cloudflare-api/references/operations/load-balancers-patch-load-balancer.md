# PATCH /zones/{zone_id}/load_balancers/{load_balancer_id}

**Resource:** [Load Balancers](../resources/Load-Balancers.md)
**Patch Load Balancer**
**Operation ID:** `load-balancers-patch-load-balancer`

Apply changes to an existing load balancer, overwriting the supplied properties.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | load-balancing_load-balancer_components-schemas-identifier | Yes |  |
| `load_balancer_id` | path | load-balancing_load-balancer_components-schemas-identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Patch Load Balancer response. |
| 4XX | Patch Load Balancer response failure. |

**Success Response Schema:**

[load-balancing_load-balancer_components-schemas-single_response](../schemas/load-balancing/load-balancing-load-balancer-components-schemas-single-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**

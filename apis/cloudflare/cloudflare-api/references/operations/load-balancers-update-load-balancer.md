# PUT /zones/{zone_id}/load_balancers/{load_balancer_id}

**Resource:** [Load Balancers](../resources/Load-Balancers.md)
**Update Load Balancer**
**Operation ID:** `load-balancers-update-load-balancer`

Update a configured load balancer.

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
| 200 | Update Load Balancer response. |
| 4XX | Update Load Balancer response failure. |

**Success Response Schema:**

[load-balancing_load-balancer_components-schemas-single_response](../schemas/load-balancing/load-balancing-load-balancer-components-schemas-single-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**

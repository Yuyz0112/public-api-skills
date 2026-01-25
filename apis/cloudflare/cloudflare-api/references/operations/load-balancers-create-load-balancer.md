# POST /zones/{zone_id}/load_balancers

**Resource:** [Load Balancers](../resources/Load-Balancers.md)
**Create Load Balancer**
**Operation ID:** `load-balancers-create-load-balancer`

Create a new load balancer.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | load-balancing_load-balancer_components-schemas-identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Create Load Balancer response. |
| 4XX | Create Load Balancer response failure. |

**Success Response Schema:**

[load-balancing_load-balancer_components-schemas-single_response](../schemas/load-balancing/load-balancing-load-balancer-components-schemas-single-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**

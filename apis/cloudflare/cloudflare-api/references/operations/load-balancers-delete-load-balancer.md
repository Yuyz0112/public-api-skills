# DELETE /zones/{zone_id}/load_balancers/{load_balancer_id}

**Resource:** [Load Balancers](../resources/Load-Balancers.md)
**Delete Load Balancer**
**Operation ID:** `load-balancers-delete-load-balancer`

Delete a configured load balancer.

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
| 200 | Delete Load Balancer response. |
| 4XX | Delete Load Balancer response failure. |

**Success Response Schema:**

[load-balancing_components-schemas-id_response](../schemas/load-balancing/load-balancing-components-schemas-id-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**

# GET /zones/{zone_id}/load_balancers/{load_balancer_id}

**Resource:** [Load Balancers](../resources/Load-Balancers.md)
**Load Balancer Details**
**Operation ID:** `load-balancers-load-balancer-details`

Fetch a single configured load balancer.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | load-balancing_load-balancer_components-schemas-identifier | Yes |  |
| `load_balancer_id` | path | load-balancing_load-balancer_components-schemas-identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Load Balancer Details response. |
| 4XX | Load Balancer Details response failure. |

**Success Response Schema:**

[load-balancing_load-balancer_components-schemas-single_response](../schemas/load-balancing/load-balancing-load-balancer-components-schemas-single-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**

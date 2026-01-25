# GET /zones/{zone_id}/load_balancers

**Resource:** [Load Balancers](../resources/Load-Balancers.md)
**List Load Balancers**
**Operation ID:** `load-balancers-list-load-balancers`

List configured load balancers.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | load-balancing_load-balancer_components-schemas-identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List Load Balancers response. |
| 4XX | List Load Balancers response failure. |

**Success Response Schema:**

[load-balancing_load-balancer_components-schemas-response_collection](../schemas/load-balancing/load-balancing-load-balancer-components-schemas-response-collection.md)

## Security

- **api_email**
- **api_key**
- **api_token**

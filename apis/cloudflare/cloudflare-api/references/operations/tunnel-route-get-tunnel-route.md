# GET /accounts/{account_id}/teamnet/routes/{route_id}

**Resource:** [Tunnel Routing](../resources/Tunnel-Routing.md)
**Get tunnel route**
**Operation ID:** `tunnel-route-get-tunnel-route`

Get a private network route in an account.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | tunnel_account_id | Yes |  |
| `route_id` | path | tunnel_route_id | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get a tunnel route response |
| 4XX | Get a tunnel route response failure |

**Success Response Schema:**

[tunnel_route_response_single](../schemas/tunnel/tunnel-route-response-single.md)

## Security

- **api_email**
- **api_key**
- **api_token**
- **user_service_key**

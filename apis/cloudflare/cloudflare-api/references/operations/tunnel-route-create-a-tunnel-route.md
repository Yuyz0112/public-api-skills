# POST /accounts/{account_id}/teamnet/routes

**Resource:** [Tunnel Routing](../resources/Tunnel-Routing.md)
**Create a tunnel route**
**Operation ID:** `tunnel-route-create-a-tunnel-route`

Routes a private network through a Cloudflare Tunnel.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | tunnel_account_id | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Create a tunnel route response |
| 4XX | Create a tunnel route response failure |

**Success Response Schema:**

[tunnel_route_response_single](../schemas/tunnel/tunnel-route-response-single.md)

## Security

- **api_email**
- **api_key**
- **api_token**
- **user_service_key**

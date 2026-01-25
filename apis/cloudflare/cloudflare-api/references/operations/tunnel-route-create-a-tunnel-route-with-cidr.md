# POST /accounts/{account_id}/teamnet/routes/network/{ip_network_encoded}

**Resource:** [Tunnel Routing](../resources/Tunnel-Routing.md)
**Create a tunnel route (CIDR Endpoint)**
**Operation ID:** `tunnel-route-create-a-tunnel-route-with-cidr`
⚠️ **Deprecated**

Routes a private network through a Cloudflare Tunnel. The CIDR in `ip_network_encoded` must be written in URL-encoded format.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `ip_network_encoded` | path | tunnel_ip_network_encoded | Yes |  |
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

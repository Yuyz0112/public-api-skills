# DELETE /accounts/{account_id}/teamnet/routes/network/{ip_network_encoded}

**Resource:** [Tunnel Routing](../resources/Tunnel-Routing.md)
**Delete a tunnel route (CIDR Endpoint)**
**Operation ID:** `tunnel-route-delete-a-tunnel-route-with-cidr`
⚠️ **Deprecated**

Deletes a private network route from an account. The CIDR in `ip_network_encoded` must be written in URL-encoded format. If no virtual_network_id is provided it will delete the route from the default vnet. If no tun_type is provided it will fetch the type from the tunnel_id or if that is missing it will assume Cloudflare Tunnel as default. If tunnel_id is provided it will delete the route from that tunnel, otherwise it will delete the route based on the vnet and tun_type.


## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `ip_network_encoded` | path | tunnel_ip_network_encoded | Yes |  |
| `account_id` | path | tunnel_account_id | Yes |  |
| `virtual_network_id` | query | tunnel_virtual_network_id | No |  |
| `tun_type` | query | tunnel_tunnel_type | No |  |
| `tunnel_id` | query | tunnel_tunnel_id | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Delete a tunnel route response |
| 4XX | Delete a tunnel route response failure |

**Success Response Schema:**

[tunnel_route_response_single](../schemas/tunnel/tunnel-route-response-single.md)

## Security

- **api_email**
- **api_key**
- **api_token**
- **user_service_key**

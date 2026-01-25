# DELETE /accounts/{account_id}/cfd_tunnel/{tunnel_id}/connections

**Resource:** [Cloudflare Tunnel](../resources/Cloudflare-Tunnel.md)
**Clean up Cloudflare Tunnel connections**
**Operation ID:** `cloudflare-tunnel-clean-up-cloudflare-tunnel-connections`

Removes a connection (aka Cloudflare Tunnel Connector) from a Cloudflare Tunnel independently of its current state. If no connector id (client_id) is provided all connectors will be removed. We recommend running this command after rotating tokens.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | tunnel_account_id | Yes |  |
| `tunnel_id` | path | tunnel_tunnel_id | Yes |  |
| `client_id` | query | tunnel_client_id | No |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Clean up Cloudflare Tunnel connections response |
| 4XX | Clean up Cloudflare Tunnel connections response failure |

**Success Response Schema:**

[tunnel_empty_response](../schemas/tunnel/tunnel-empty-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**
- **user_service_key**

# GET /accounts/{account_id}/cfd_tunnel/{tunnel_id}/connections

**Resource:** [Cloudflare Tunnel](../resources/Cloudflare-Tunnel.md)
**List Cloudflare Tunnel connections**
**Operation ID:** `cloudflare-tunnel-list-cloudflare-tunnel-connections`

Fetches connection details for a Cloudflare Tunnel.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | tunnel_account_id | Yes |  |
| `tunnel_id` | path | tunnel_tunnel_id | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List Cloudflare Tunnel connections response |
| 4XX | List Cloudflare Tunnel connections response failure |

**Success Response Schema:**

[tunnel_tunnel_connections_response](../schemas/tunnel/tunnel-tunnel-connections-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**
- **user_service_key**

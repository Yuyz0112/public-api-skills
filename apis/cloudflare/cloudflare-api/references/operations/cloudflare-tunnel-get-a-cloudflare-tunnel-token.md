# GET /accounts/{account_id}/cfd_tunnel/{tunnel_id}/token

**Resource:** [Cloudflare Tunnel](../resources/Cloudflare-Tunnel.md)
**Get a Cloudflare Tunnel token**
**Operation ID:** `cloudflare-tunnel-get-a-cloudflare-tunnel-token`

Gets the token used to associate cloudflared with a specific tunnel.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | tunnel_account_id | Yes |  |
| `tunnel_id` | path | tunnel_tunnel_id | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get a Cloudflare Tunnel token response |
| 4XX | Get a Cloudflare Tunnel token response failure |

**Success Response Schema:**

[tunnel_tunnel_response_token](../schemas/tunnel/tunnel-tunnel-response-token.md)

## Security

- **api_email**
- **api_key**
- **api_token**
- **user_service_key**

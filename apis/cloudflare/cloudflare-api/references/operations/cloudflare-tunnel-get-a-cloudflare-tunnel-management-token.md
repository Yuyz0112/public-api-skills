# POST /accounts/{account_id}/cfd_tunnel/{tunnel_id}/management

**Resource:** [Cloudflare Tunnel](../resources/Cloudflare-Tunnel.md)
**Get a Cloudflare Tunnel management token**
**Operation ID:** `cloudflare-tunnel-get-a-cloudflare-tunnel-management-token`

Gets a management token used to access the management resources (i.e. Streaming Logs) of a tunnel.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | tunnel_account_id | Yes |  |
| `tunnel_id` | path | tunnel_tunnel_id | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get a Cloudflare Tunnel management token response |
| 4XX | Cloudflare API response failure |

**Success Response Schema:**

[tunnel_tunnel_response_token](../schemas/tunnel/tunnel-tunnel-response-token.md)

## Security

- **api_email**
- **api_key**
- **api_token**
- **user_service_key**

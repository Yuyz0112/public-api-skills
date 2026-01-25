# GET /accounts/{account_id}/cfd_tunnel/{tunnel_id}/connectors/{connector_id}

**Resource:** [Cloudflare Tunnel](../resources/Cloudflare-Tunnel.md)
**Get Cloudflare Tunnel connector**
**Operation ID:** `cloudflare-tunnel-get-cloudflare-tunnel-connector`

Fetches connector and connection details for a Cloudflare Tunnel.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | tunnel_account_id | Yes |  |
| `tunnel_id` | path | tunnel_tunnel_id | Yes |  |
| `connector_id` | path | tunnel_client_id | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get Cloudflare Tunnel connector response |
| 4XX | Get Cloudflare Tunnel connector response failure |

**Success Response Schema:**

[tunnel_tunnel_client_response](../schemas/tunnel/tunnel-tunnel-client-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**
- **user_service_key**

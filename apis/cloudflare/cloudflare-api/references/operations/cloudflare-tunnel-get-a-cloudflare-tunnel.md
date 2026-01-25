# GET /accounts/{account_id}/cfd_tunnel/{tunnel_id}

**Resource:** [Cloudflare Tunnel](../resources/Cloudflare-Tunnel.md)
**Get a Cloudflare Tunnel**
**Operation ID:** `cloudflare-tunnel-get-a-cloudflare-tunnel`

Fetches a single Cloudflare Tunnel.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | tunnel_account_id | Yes |  |
| `tunnel_id` | path | tunnel_tunnel_id | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get a Cloudflare Tunnel response |
| 4XX | Get a Cloudflare Tunnel response failure |

**Success Response Schema:**

[tunnel_cfd-tunnel-response-single](../schemas/tunnel/tunnel-cfd-tunnel-response-single.md)

## Security

- **api_email**
- **api_key**
- **api_token**
- **user_service_key**

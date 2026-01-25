# GET /accounts/{account_id}/warp_connector/{tunnel_id}

**Resource:** [Cloudflare Tunnel](../resources/Cloudflare-Tunnel.md)
**Get a Warp Connector Tunnel**
**Operation ID:** `cloudflare-tunnel-get-a-warp-connector-tunnel`

Fetches a single Warp Connector Tunnel.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | tunnel_account_id | Yes |  |
| `tunnel_id` | path | tunnel_tunnel_id | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get a Warp Connector Tunnel response |
| 4XX | Get a Warp Connector Tunnel response failure |

**Success Response Schema:**

[tunnel_warp-connector-response-single](../schemas/tunnel/tunnel-warp-connector-response-single.md)

## Security

- **api_email**
- **api_key**
- **api_token**
- **user_service_key**

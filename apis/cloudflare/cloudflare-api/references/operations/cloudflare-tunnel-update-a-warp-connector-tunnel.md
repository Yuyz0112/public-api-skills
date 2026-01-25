# PATCH /accounts/{account_id}/warp_connector/{tunnel_id}

**Resource:** [Cloudflare Tunnel](../resources/Cloudflare-Tunnel.md)
**Update a Warp Connector Tunnel**
**Operation ID:** `cloudflare-tunnel-update-a-warp-connector-tunnel`

Updates an existing Warp Connector Tunnel.

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
| 200 | Update a Warp Connector Tunnel response |
| 4XX | Update a Warp Connector Tunnel response failure |

**Success Response Schema:**

[tunnel_warp-connector-response-single](../schemas/tunnel/tunnel-warp-connector-response-single.md)

## Security

- **api_email**
- **api_key**
- **api_token**
- **user_service_key**

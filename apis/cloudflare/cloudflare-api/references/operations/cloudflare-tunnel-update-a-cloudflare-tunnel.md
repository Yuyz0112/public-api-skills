# PATCH /accounts/{account_id}/cfd_tunnel/{tunnel_id}

**Resource:** [Cloudflare Tunnel](../resources/Cloudflare-Tunnel.md)
**Update a Cloudflare Tunnel**
**Operation ID:** `cloudflare-tunnel-update-a-cloudflare-tunnel`

Updates an existing Cloudflare Tunnel.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `tunnel_id` | path | tunnel_tunnel_id | Yes |  |
| `account_id` | path | tunnel_account_id | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Update a Cloudflare Tunnel response |
| 4XX | Update a Cloudflare Tunnel response failure |

**Success Response Schema:**

[tunnel_cfd-tunnel-response-single](../schemas/tunnel/tunnel-cfd-tunnel-response-single.md)

## Security

- **api_email**
- **api_key**
- **api_token**
- **user_service_key**

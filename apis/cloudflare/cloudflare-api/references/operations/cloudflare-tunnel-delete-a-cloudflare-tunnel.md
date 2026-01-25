# DELETE /accounts/{account_id}/cfd_tunnel/{tunnel_id}

**Resource:** [Cloudflare Tunnel](../resources/Cloudflare-Tunnel.md)
**Delete a Cloudflare Tunnel**
**Operation ID:** `cloudflare-tunnel-delete-a-cloudflare-tunnel`

Deletes a Cloudflare Tunnel from an account.

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
| 200 | Delete a Cloudflare Tunnel response |
| 4XX | Delete a Cloudflare Tunnel response failure |

**Success Response Schema:**

[tunnel_cfd-tunnel-response-single](../schemas/tunnel/tunnel-cfd-tunnel-response-single.md)

## Security

- **api_email**
- **api_key**
- **api_token**
- **user_service_key**

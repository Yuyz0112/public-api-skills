# POST /accounts/{account_id}/cfd_tunnel

**Resource:** [Cloudflare Tunnel](../resources/Cloudflare-Tunnel.md)
**Create a Cloudflare Tunnel**
**Operation ID:** `cloudflare-tunnel-create-a-cloudflare-tunnel`

Creates a new Cloudflare Tunnel in an account.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | tunnel_account_id | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Create a Cloudflare Tunnel response |
| 4XX | Create a Cloudflare Tunnel response failure |

**Success Response Schema:**

[tunnel_cfd-tunnel-response-single](../schemas/tunnel/tunnel-cfd-tunnel-response-single.md)

## Security

- **api_email**
- **api_key**
- **api_token**
- **user_service_key**

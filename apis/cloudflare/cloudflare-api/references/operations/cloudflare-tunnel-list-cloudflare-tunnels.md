# GET /accounts/{account_id}/cfd_tunnel

**Resource:** [Cloudflare Tunnel](../resources/Cloudflare-Tunnel.md)
**List Cloudflare Tunnels**
**Operation ID:** `cloudflare-tunnel-list-cloudflare-tunnels`

Lists and filters Cloudflare Tunnels in an account.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | tunnel_account_id | Yes |  |
| `name` | query | tunnel_tunnel_name | No |  |
| `is_deleted` | query | boolean | No |  |
| `existed_at` | query | tunnel_existed_at | No |  |
| `uuid` | query | tunnel_tunnel_id | No |  |
| `was_active_at` | query | string (date-time) | No |  |
| `was_inactive_at` | query | string (date-time) | No |  |
| `include_prefix` | query | string | No |  |
| `exclude_prefix` | query | string | No |  |
| `status` | query | tunnel_status | No |  |
| `per_page` | query | tunnel_per_page | No |  |
| `page` | query | tunnel_page_number | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List Cloudflare Tunnels response |
| 4XX | List Cloudflare Tunnels response failure |

**Success Response Schema:**

[tunnel_cfd-tunnel-response-collection](../schemas/tunnel/tunnel-cfd-tunnel-response-collection.md)

## Security

- **api_email**
- **api_key**
- **api_token**
- **user_service_key**

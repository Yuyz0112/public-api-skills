# GET /accounts/{account_id}/tunnels

**Resource:** [Cloudflare Tunnel](../resources/Cloudflare-Tunnel.md)
**List All Tunnels**
**Operation ID:** `cloudflare-tunnel-list-all-tunnels`

Lists and filters all types of Tunnels in an account.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | tunnel_account_id | Yes |  |
| `name` | query | string | No |  |
| `is_deleted` | query | boolean | No |  |
| `existed_at` | query | tunnel_existed_at | No |  |
| `uuid` | query | tunnel_tunnel_id | No |  |
| `was_active_at` | query | string (date-time) | No |  |
| `was_inactive_at` | query | string (date-time) | No |  |
| `include_prefix` | query | string | No |  |
| `exclude_prefix` | query | string | No |  |
| `tun_types` | query | tunnel_tunnel_types | No |  |
| `status` | query | tunnel_status | No |  |
| `per_page` | query | tunnel_per_page | No |  |
| `page` | query | tunnel_page_number | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List Tunnels response |
| 4XX | List Tunnels response failure |

**Success Response Schema:**

[tunnel_tunnel-response-collection](../schemas/tunnel/tunnel-tunnel-response-collection.md)

## Security

- **api_email**
- **api_key**
- **api_token**
- **user_service_key**

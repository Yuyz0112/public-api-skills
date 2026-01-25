# GET /accounts/{account_id}/teamnet/routes

**Resource:** [Tunnel Routing](../resources/Tunnel-Routing.md)
**List tunnel routes**
**Operation ID:** `tunnel-route-list-tunnel-routes`

Lists and filters private network routes in an account.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | tunnel_account_id | Yes |  |
| `comment` | query | tunnel_route_comment | No |  |
| `is_deleted` | query | boolean | No |  |
| `network_subset` | query | any | No |  |
| `network_superset` | query | any | No |  |
| `existed_at` | query | tunnel_existed_at | No |  |
| `tunnel_id` | query | tunnel_tunnel_id | No |  |
| `route_id` | query | tunnel_route_id | No |  |
| `tun_types` | query | tunnel_tunnel_types | No |  |
| `virtual_network_id` | query | tunnel_virtual_network_id | No |  |
| `per_page` | query | tunnel_per_page | No |  |
| `page` | query | tunnel_page_number | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List tunnel routes response |
| 4XX | List tunnel routes response failure |

**Success Response Schema:**

[tunnel_teamnet_response_collection](../schemas/tunnel/tunnel-teamnet-response-collection.md)

## Security

- **api_email**
- **api_key**
- **api_token**
- **user_service_key**

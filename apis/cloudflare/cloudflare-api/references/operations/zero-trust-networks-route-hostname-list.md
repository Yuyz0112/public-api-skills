# GET /accounts/{account_id}/zerotrust/routes/hostname

**Resource:** [Zero Trust Hostname Route](../resources/Zero-Trust-Hostname-Route.md)
**List hostname routes**
**Operation ID:** `zero-trust-networks-route-hostname-list`

Lists and filters hostname routes in an account.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | tunnel_account_id | Yes |  |
| `id` | query | tunnel_hostname_route_id | No |  |
| `hostname` | query | tunnel_hostname | No | If set, only list hostname routes that contain a substring of the given value, the filter is case-insensitive. |
| `tunnel_id` | query | tunnel_components-schemas-tunnel_id | No | If set, only list hostname routes that point to a specific tunnel. |
| `comment` | query | tunnel_hostname_query_comment | No |  |
| `existed_at` | query | tunnel_existed_at | No |  |
| `is_deleted` | query | boolean | No |  |
| `per_page` | query | tunnel_per_page | No |  |
| `page` | query | tunnel_page_number | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List hostname routes response |
| 4XX | List hostname routes failure |

**Success Response Schema:**

[tunnel_hostname_route_response_collection](../schemas/tunnel/tunnel-hostname-route-response-collection.md)

## Security

- **api_email**
- **api_key**
- **api_token**
- **user_service_key**

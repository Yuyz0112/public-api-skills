# GET /accounts/{account_id}/teamnet/routes/ip/{ip}

**Resource:** [Tunnel Routing](../resources/Tunnel-Routing.md)
**Get tunnel route by IP**
**Operation ID:** `tunnel-route-get-tunnel-route-by-ip`

Fetches routes that contain the given IP address.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `ip` | path | tunnel_ip | Yes |  |
| `account_id` | path | tunnel_account_id | Yes |  |
| `virtual_network_id` | query | tunnel_virtual_network_id | No |  |
| `default_virtual_network_fallback` | query | boolean | No | When the virtual_network_id parameter is not provided the request filter will default search routes that are in the default virtual network for the account. If this parameter is set to false, the search will include routes that do not have a virtual network. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get tunnel route by IP response |
| 4XX | Get tunnel route by IP response failure |

**Success Response Schema:**

[tunnel_teamnet_response_single](../schemas/tunnel/tunnel-teamnet-response-single.md)

## Security

- **api_email**
- **api_key**
- **api_token**
- **user_service_key**

# GET /accounts/{account_id}/cfd_tunnel/{tunnel_id}/configurations

**Resource:** [Cloudflare Tunnel Configuration](../resources/Cloudflare-Tunnel-Configuration.md)
**Get configuration**
**Operation ID:** `cloudflare-tunnel-configuration-get-configuration`

Gets the configuration for a remotely-managed tunnel

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | tunnel_identifier | Yes |  |
| `tunnel_id` | path | tunnel_schemas-tunnel_id | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get configuration response |
| 4XX | Get configuration response failure |

**Success Response Schema:**

[tunnel_configuration_response](../schemas/tunnel/tunnel-configuration-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**
- **user_service_key**

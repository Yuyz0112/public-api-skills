# PUT /accounts/{account_id}/cfd_tunnel/{tunnel_id}/configurations

**Resource:** [Cloudflare Tunnel Configuration](../resources/Cloudflare-Tunnel-Configuration.md)
**Put configuration**
**Operation ID:** `cloudflare-tunnel-configuration-put-configuration`

Adds or updates the configuration for a remotely-managed tunnel.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | tunnel_identifier | Yes |  |
| `tunnel_id` | path | tunnel_schemas-tunnel_id | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Put configuration response |
| 4XX | Put configuration response failure |

**Success Response Schema:**

[tunnel_configuration_response](../schemas/tunnel/tunnel-configuration-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**
- **user_service_key**

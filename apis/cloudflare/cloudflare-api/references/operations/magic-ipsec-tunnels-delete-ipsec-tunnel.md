# DELETE /accounts/{account_id}/magic/ipsec_tunnels/{ipsec_tunnel_id}

**Resource:** [Magic IPsec tunnels](../resources/Magic-IPsec-tunnels.md)
**Delete IPsec Tunnel**
**Operation ID:** `magic-ipsec-tunnels-delete-ipsec-tunnel`

Disables and removes a specific static IPsec Tunnel associated with an account. Use `?validate_only=true` as an optional query parameter to only run validation without persisting changes.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `ipsec_tunnel_id` | path | magic_identifier | Yes |  |
| `account_id` | path | magic_identifier | Yes |  |
| `x-magic-new-hc-target` | header | boolean | No | If true, the health check target in the response body will be presented using the new object format. Defaults to false. |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Delete IPsec Tunnel response |
| 4XX | Delete IPsec Tunnel response failure |

**Success Response Schema:**

[magic_schemas-tunnel_deleted_response](../schemas/magic/magic-schemas-tunnel-deleted-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**

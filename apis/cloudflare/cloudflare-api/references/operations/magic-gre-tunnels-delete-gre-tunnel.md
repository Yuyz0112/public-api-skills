# DELETE /accounts/{account_id}/magic/gre_tunnels/{gre_tunnel_id}

**Resource:** [Magic GRE tunnels](../resources/Magic-GRE-tunnels.md)
**Delete GRE Tunnel**
**Operation ID:** `magic-gre-tunnels-delete-gre-tunnel`

Disables and removes a specific static GRE tunnel. Use `?validate_only=true` as an optional query parameter to only run validation without persisting changes.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `gre_tunnel_id` | path | magic_identifier | Yes |  |
| `account_id` | path | magic_identifier | Yes |  |
| `x-magic-new-hc-target` | header | boolean | No | If true, the health check target in the response body will be presented using the new object format. Defaults to false. |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Delete GRE Tunnel response |
| 4XX | Delete GRE Tunnel response failure |

**Success Response Schema:**

[magic_tunnel_deleted_response](../schemas/magic/magic-tunnel-deleted-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**

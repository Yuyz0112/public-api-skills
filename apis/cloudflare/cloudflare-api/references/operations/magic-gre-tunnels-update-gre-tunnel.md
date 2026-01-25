# PUT /accounts/{account_id}/magic/gre_tunnels/{gre_tunnel_id}

**Resource:** [Magic GRE tunnels](../resources/Magic-GRE-tunnels.md)
**Update GRE Tunnel**
**Operation ID:** `magic-gre-tunnels-update-gre-tunnel`

Updates a specific GRE tunnel. Use `?validate_only=true` as an optional query parameter to only run validation without persisting changes.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `gre_tunnel_id` | path | magic_identifier | Yes |  |
| `account_id` | path | magic_identifier | Yes |  |
| `x-magic-new-hc-target` | header | boolean | No | If true, the health check target in the request and response bodies will be presented using the new object format. Defaults to false. |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [magic_gre_tunnel_update_request](../schemas/magic/magic-gre-tunnel-update-request.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Update GRE Tunnel response |
| 4XX | Update GRE Tunnel response failure |

**Success Response Schema:**

[magic_tunnel_modified_response](../schemas/magic/magic-tunnel-modified-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**

# POST /accounts/{account_id}/magic/gre_tunnels

**Resource:** [Magic GRE tunnels](../resources/Magic-GRE-tunnels.md)
**Create a GRE tunnel**
**Operation ID:** `magic-gre-tunnels-create-gre-tunnels`

Creates a new GRE tunnel. Use `?validate_only=true` as an optional query parameter to only run validation without persisting changes.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | magic_identifier | Yes |  |
| `x-magic-new-hc-target` | header | boolean | No | If true, the health check target in the request and response bodies will be presented using the new object format. Defaults to false. |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [magic_create_gre_tunnel_request](../schemas/magic/magic-create-gre-tunnel-request.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Create GRE tunnels response |
| 4XX | Create GRE tunnels response failure |

**Success Response Schema:**

[magic_create_gre_tunnel_response](../schemas/magic/magic-create-gre-tunnel-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**

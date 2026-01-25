# POST /accounts/{account_id}/magic/ipsec_tunnels

**Resource:** [Magic IPsec tunnels](../resources/Magic-IPsec-tunnels.md)
**Create an IPsec tunnel**
**Operation ID:** `magic-ipsec-tunnels-create-ipsec-tunnels`

Creates a new IPsec tunnel associated with an account. Use `?validate_only=true` as an optional query parameter to only run validation without persisting changes.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | magic_identifier | Yes |  |
| `x-magic-new-hc-target` | header | boolean | No | If true, the health check target in the request and response bodies will be presented using the new object format. Defaults to false. |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [magic_ipsec_tunnel_add_request](../schemas/magic/magic-ipsec-tunnel-add-request.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Create IPsec tunnels response |
| 4XX | Create IPsec tunnels response failure |

**Success Response Schema:**

[magic_schemas-create_ipsec_tunnel_response](../schemas/magic/magic-schemas-create-ipsec-tunnel-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**

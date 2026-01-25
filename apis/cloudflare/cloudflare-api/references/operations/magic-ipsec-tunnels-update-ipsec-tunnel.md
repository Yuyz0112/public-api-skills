# PUT /accounts/{account_id}/magic/ipsec_tunnels/{ipsec_tunnel_id}

**Resource:** [Magic IPsec tunnels](../resources/Magic-IPsec-tunnels.md)
**Update IPsec Tunnel**
**Operation ID:** `magic-ipsec-tunnels-update-ipsec-tunnel`

Updates a specific IPsec tunnel associated with an account. Use `?validate_only=true` as an optional query parameter to only run validation without persisting changes.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `ipsec_tunnel_id` | path | magic_identifier | Yes |  |
| `account_id` | path | magic_identifier | Yes |  |
| `x-magic-new-hc-target` | header | boolean | No | If true, the health check target in the request and response bodies will be presented using the new object format. Defaults to false. |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [magic_ipsec_tunnel_add_single_request](../schemas/magic/magic-ipsec-tunnel-add-single-request.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Update IPsec Tunnel response |
| 4XX | Update IPsec Tunnel response failure |

**Success Response Schema:**

[magic_schemas-tunnel_modified_response](../schemas/magic/magic-schemas-tunnel-modified-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**

# GET /accounts/{account_id}/magic/ipsec_tunnels/{ipsec_tunnel_id}

**Resource:** [Magic IPsec tunnels](../resources/Magic-IPsec-tunnels.md)
**List IPsec tunnel details**
**Operation ID:** `magic-ipsec-tunnels-list-ipsec-tunnel-details`

Lists details for a specific IPsec tunnel.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `ipsec_tunnel_id` | path | magic_identifier | Yes |  |
| `account_id` | path | magic_identifier | Yes |  |
| `x-magic-new-hc-target` | header | boolean | No | If true, the health check target in the response body will be presented using the new object format. Defaults to false. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List IPsec tunnel details response |
| 4XX | List IPsec tunnel details response failure |

**Success Response Schema:**

[magic_schemas-tunnel_single_response](../schemas/magic/magic-schemas-tunnel-single-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**

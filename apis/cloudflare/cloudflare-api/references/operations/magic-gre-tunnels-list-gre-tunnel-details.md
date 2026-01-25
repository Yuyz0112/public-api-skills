# GET /accounts/{account_id}/magic/gre_tunnels/{gre_tunnel_id}

**Resource:** [Magic GRE tunnels](../resources/Magic-GRE-tunnels.md)
**List GRE Tunnel Details**
**Operation ID:** `magic-gre-tunnels-list-gre-tunnel-details`

Lists informtion for a specific GRE tunnel.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `gre_tunnel_id` | path | magic_identifier | Yes |  |
| `account_id` | path | magic_identifier | Yes |  |
| `x-magic-new-hc-target` | header | boolean | No | If true, the health check target in the response body will be presented using the new object format. Defaults to false. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List GRE Tunnel Details response |
| 4XX | List GRE Tunnel Details response failure |

**Success Response Schema:**

[magic_tunnel_single_response](../schemas/magic/magic-tunnel-single-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**

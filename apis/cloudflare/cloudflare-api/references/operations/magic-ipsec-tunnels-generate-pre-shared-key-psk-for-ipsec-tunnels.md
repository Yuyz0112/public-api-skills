# POST /accounts/{account_id}/magic/ipsec_tunnels/{ipsec_tunnel_id}/psk_generate

**Resource:** [Magic IPsec tunnels](../resources/Magic-IPsec-tunnels.md)
**Generate Pre Shared Key (PSK) for IPsec tunnels**
**Operation ID:** `magic-ipsec-tunnels-generate-pre-shared-key-(-psk)-for-ipsec-tunnels`

Generates a Pre Shared Key for a specific IPsec tunnel used in the IKE session. Use `?validate_only=true` as an optional query parameter to only run validation without persisting changes. After a PSK is generated, the PSK is immediately persisted to Cloudflare's edge and cannot be retrieved later. Note the PSK in a safe place.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `ipsec_tunnel_id` | path | magic_identifier | Yes |  |
| `account_id` | path | magic_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Generate Pre Shared Key (PSK) for IPsec tunnels response |
| 4XX | Generate Pre Shared Key (PSK) for IPsec tunnels response failure |

**Success Response Schema:**

[magic_psk_generation_response](../schemas/magic/magic-psk-generation-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**

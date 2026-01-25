# PUT /accounts/{account_id}/magic/ipsec_tunnels

**Resource:** [Magic IPsec tunnels](../resources/Magic-IPsec-tunnels.md)
**Update multiple IPsec tunnels**
**Operation ID:** `magic-ipsec-tunnels-update-multiple-ipsec-tunnels`

Update multiple IPsec tunnels associated with an account. Use `?validate_only=true` as an optional query parameter to only run validation without persisting changes.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | magic_identifier | Yes |  |
| `x-magic-new-hc-target` | header | boolean | No | If true, the health check target in the request and response bodies will be presented using the new object format. Defaults to false. |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Update multiple IPsec tunnels response |
| 4XX | Update multiple IPsec tunnels response failure |

**Success Response Schema:**

[magic_schemas-modified_tunnels_collection_response](../schemas/magic/magic-schemas-modified-tunnels-collection-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**

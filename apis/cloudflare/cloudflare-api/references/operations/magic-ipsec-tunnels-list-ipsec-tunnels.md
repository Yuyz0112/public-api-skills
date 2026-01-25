# GET /accounts/{account_id}/magic/ipsec_tunnels

**Resource:** [Magic IPsec tunnels](../resources/Magic-IPsec-tunnels.md)
**List IPsec tunnels**
**Operation ID:** `magic-ipsec-tunnels-list-ipsec-tunnels`

Lists IPsec tunnels associated with an account.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | magic_identifier | Yes |  |
| `x-magic-new-hc-target` | header | boolean | No | If true, the health check target in the response body will be presented using the new object format. Defaults to false. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List IPsec tunnels response |
| 4XX | List IPsec tunnels response failure |

**Success Response Schema:**

[magic_schemas-tunnels_collection_response](../schemas/magic/magic-schemas-tunnels-collection-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**

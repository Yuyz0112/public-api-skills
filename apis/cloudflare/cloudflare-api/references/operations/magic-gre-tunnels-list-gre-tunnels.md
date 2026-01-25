# GET /accounts/{account_id}/magic/gre_tunnels

**Resource:** [Magic GRE tunnels](../resources/Magic-GRE-tunnels.md)
**List GRE tunnels**
**Operation ID:** `magic-gre-tunnels-list-gre-tunnels`

Lists GRE tunnels associated with an account.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | magic_identifier | Yes |  |
| `x-magic-new-hc-target` | header | boolean | No | If true, the health check target in the response body will be presented using the new object format. Defaults to false. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List GRE tunnels response |
| 4XX | List GRE tunnels response failure |

**Success Response Schema:**

[magic_tunnels_collection_response](../schemas/magic/magic-tunnels-collection-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**

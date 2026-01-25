# PUT /accounts/{account_id}/magic/gre_tunnels

**Resource:** [Magic GRE tunnels](../resources/Magic-GRE-tunnels.md)
**Update multiple GRE tunnels**
**Operation ID:** `magic-gre-tunnels-update-multiple-gre-tunnels`

Updates multiple GRE tunnels. Use `?validate_only=true` as an optional query parameter to only run validation without persisting changes.

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
| 200 | Update multiple GRE tunnels response |
| 4XX | Update multiple GRE tunnels response failure |

**Success Response Schema:**

[magic_modified_tunnels_collection_response](../schemas/magic/magic-modified-tunnels-collection-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**

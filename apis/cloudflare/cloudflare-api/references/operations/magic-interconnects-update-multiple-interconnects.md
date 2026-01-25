# PUT /accounts/{account_id}/magic/cf_interconnects

**Resource:** [Magic Interconnects](../resources/Magic-Interconnects.md)
**Update multiple interconnects**
**Operation ID:** `magic-interconnects-update-multiple-interconnects`

Updates multiple interconnects associated with an account. Use `?validate_only=true` as an optional query parameter to only run validation without persisting changes.

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
| 200 | Update multiple interconnects response |
| 4XX | Update multiple interconnects response failure |

**Success Response Schema:**

[magic_components-schemas-modified_tunnels_collection_response](../schemas/magic/magic-components-schemas-modified-tunnels-collection-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**

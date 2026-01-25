# PUT /accounts/{account_id}/magic/cf_interconnects/{cf_interconnect_id}

**Resource:** [Magic Interconnects](../resources/Magic-Interconnects.md)
**Update interconnect**
**Operation ID:** `magic-interconnects-update-interconnect`

Updates a specific interconnect associated with an account. Use `?validate_only=true` as an optional query parameter to only run validation without persisting changes.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `cf_interconnect_id` | path | magic_identifier | Yes |  |
| `account_id` | path | magic_identifier | Yes |  |
| `x-magic-new-hc-target` | header | boolean | No | If true, the health check target in the request and response bodies will be presented using the new object format. Defaults to false. |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [magic_interconnect_tunnel_update_request](../schemas/magic/magic-interconnect-tunnel-update-request.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Update interconnect response |
| 4XX | Update interconnect response failure |

**Success Response Schema:**

[magic_components-schemas-tunnel_modified_response](../schemas/magic/magic-components-schemas-tunnel-modified-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**

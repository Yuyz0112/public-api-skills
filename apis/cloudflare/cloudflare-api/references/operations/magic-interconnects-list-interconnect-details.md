# GET /accounts/{account_id}/magic/cf_interconnects/{cf_interconnect_id}

**Resource:** [Magic Interconnects](../resources/Magic-Interconnects.md)
**List interconnect Details**
**Operation ID:** `magic-interconnects-list-interconnect-details`

Lists details for a specific interconnect.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `cf_interconnect_id` | path | magic_identifier | Yes |  |
| `account_id` | path | magic_identifier | Yes |  |
| `x-magic-new-hc-target` | header | boolean | No | If true, the health check target in the response body will be presented using the new object format. Defaults to false. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List interconnect Details response |
| 4XX | List interconnect Details response failure |

**Success Response Schema:**

[magic_components-schemas-tunnel_single_response](../schemas/magic/magic-components-schemas-tunnel-single-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**

# GET /accounts/{account_id}/magic/cf_interconnects

**Resource:** [Magic Interconnects](../resources/Magic-Interconnects.md)
**List interconnects**
**Operation ID:** `magic-interconnects-list-interconnects`

Lists interconnects associated with an account.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | magic_identifier | Yes |  |
| `x-magic-new-hc-target` | header | boolean | No | If true, the health check target in the response body will be presented using the new object format. Defaults to false. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List interconnects response |
| 4XX | List interconnects response failure |

**Success Response Schema:**

[magic_components-schemas-tunnels_collection_response](../schemas/magic/magic-components-schemas-tunnels-collection-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**

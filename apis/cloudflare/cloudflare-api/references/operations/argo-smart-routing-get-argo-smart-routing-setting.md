# GET /zones/{zone_id}/argo/smart_routing

**Resource:** [Argo Smart Routing](../resources/Argo-Smart-Routing.md)
**Get Argo Smart Routing setting**
**Operation ID:** `argo-smart-routing-get-argo-smart-routing-setting`

Retrieves the value of Argo Smart Routing enablement setting.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | argo-config_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get Argo Smart Routing enablement setting response. |
| 4XX | Get Argo Smart Routing enablement setting failure. |

**Success Response Schema:**

[argo-config_api_response_single](../schemas/argo-config/argo-config-api-response-single.md)

## Security

- **api_token**
- **api_email**
- **api_key**

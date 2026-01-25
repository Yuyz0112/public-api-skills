# PATCH /zones/{zone_id}/argo/smart_routing

**Resource:** [Argo Smart Routing](../resources/Argo-Smart-Routing.md)
**Patch Argo Smart Routing setting**
**Operation ID:** `argo-smart-routing-patch-argo-smart-routing-setting`

Configures the value of the Argo Smart Routing enablement setting.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | argo-config_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [argo-config_patch](../schemas/argo-config/argo-config-patch.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Patch Argo Smart Routing enablement setting response. |
| 4XX | Patch Argo Smart Routing enablement setting failure. |

**Success Response Schema:**

[argo-config_api_response_single](../schemas/argo-config/argo-config-api-response-single.md)

## Security

- **api_token**
- **api_email**
- **api_key**

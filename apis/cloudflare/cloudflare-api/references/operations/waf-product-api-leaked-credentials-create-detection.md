# POST /zones/{zone_id}/leaked-credential-checks/detections

**Resource:** [Leaked Credential Checks](../resources/Leaked-Credential-Checks.md)
**Create Leaked Credential Checks Custom Detection**
**Operation ID:** `waf-product-api-leaked-credentials-create-detection`

Create user-defined detection pattern for Leaked Credential Checks.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | waf-product-api-bundle_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [waf-product-api-bundle_custom-detection](../schemas/waf-product-api-bundle/waf-product-api-bundle-custom-detection.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Create Leaked Credential Checks custom detection response. |
| 4XX | Create Leaked Credential Checks custom detection failure response. |

**Success Response Schema:**

[waf-product-api-bundle_response-custom-detection](../schemas/waf-product-api-bundle/waf-product-api-bundle-response-custom-detection.md)

## Security

- **api_email**
- **api_key**
- **api_token**

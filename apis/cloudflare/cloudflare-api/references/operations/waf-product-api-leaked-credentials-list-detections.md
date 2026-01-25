# GET /zones/{zone_id}/leaked-credential-checks/detections

**Resource:** [Leaked Credential Checks](../resources/Leaked-Credential-Checks.md)
**List Leaked Credential Checks Custom Detections**
**Operation ID:** `waf-product-api-leaked-credentials-list-detections`

List user-defined detection patterns for Leaked Credential Checks.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | waf-product-api-bundle_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List Leaked Credential Checks custom detections response. |
| 4XX | List Leaked Credential Checks custom detections failure response. |

**Success Response Schema:**

[waf-product-api-bundle_response-custom-detection-collection](../schemas/waf-product-api-bundle/waf-product-api-bundle-response-custom-detection-collection.md)

## Security

- **api_email**
- **api_key**
- **api_token**

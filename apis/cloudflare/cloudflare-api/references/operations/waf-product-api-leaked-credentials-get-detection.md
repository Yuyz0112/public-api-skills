# GET /zones/{zone_id}/leaked-credential-checks/detections/{detection_id}

**Resource:** [Leaked Credential Checks](../resources/Leaked-Credential-Checks.md)
**Get Leaked Credential Checks Custom Detection**
**Operation ID:** `waf-product-api-leaked-credentials-get-detection`

Get user-defined detection pattern for Leaked Credential Checks.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | waf-product-api-bundle_identifier | Yes |  |
| `detection_id` | path | waf-product-api-bundle_detection-id | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get Leaked Credential Checks custom detection response. |
| 4XX | Update Leaked Credential Checks custom detection failure response. |

**Success Response Schema:**

[waf-product-api-bundle_response-custom-detection](../schemas/waf-product-api-bundle/waf-product-api-bundle-response-custom-detection.md)

## Security

- **api_email**
- **api_key**
- **api_token**

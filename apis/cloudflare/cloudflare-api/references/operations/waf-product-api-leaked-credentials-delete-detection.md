# DELETE /zones/{zone_id}/leaked-credential-checks/detections/{detection_id}

**Resource:** [Leaked Credential Checks](../resources/Leaked-Credential-Checks.md)
**Delete Leaked Credential Checks Custom Detection**
**Operation ID:** `waf-product-api-leaked-credentials-delete-detection`

Remove user-defined detection pattern for Leaked Credential Checks.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | waf-product-api-bundle_identifier | Yes |  |
| `detection_id` | path | waf-product-api-bundle_detection-id | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Delete Leaked Credential Checks custom detection response. |
| 4XX | Delete Leaked Credential Checks custom detection failure response. |

**Success Response Schema:**

[waf-product-api-bundle_api-response-common](../schemas/waf-product-api-bundle/waf-product-api-bundle-api-response-common.md)

## Security

- **api_email**
- **api_key**
- **api_token**

# DELETE /zones/{zone_id}/content-upload-scan/payloads/{expression_id}

**Resource:** [Content Scanning](../resources/Content-Scanning.md)
**Delete a Custom Scan Expression**
**Operation ID:** `waf-content-scanning-delete-custom-scan-expressions`

Delete a Content Scan Custom Expression.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | waf-product-api-bundle_identifier | Yes |  |
| `expression_id` | path | waf-product-api-bundle_custom-scan-id | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Delete Content Scan custom scan expressions response. |
| 4XX | Delete Content Scan custom scan expressions failure response. |

**Success Response Schema:**

[waf-product-api-bundle_response-custom-scan-collection](../schemas/waf-product-api-bundle/waf-product-api-bundle-response-custom-scan-collection.md)

## Security

- **api_email**
- **api_key**
- **api_token**

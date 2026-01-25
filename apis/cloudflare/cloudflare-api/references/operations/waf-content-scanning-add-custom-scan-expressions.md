# POST /zones/{zone_id}/content-upload-scan/payloads

**Resource:** [Content Scanning](../resources/Content-Scanning.md)
**Add Custom Scan Expressions**
**Operation ID:** `waf-content-scanning-add-custom-scan-expressions`

Add custom scan expressions for Content Scanning.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | waf-product-api-bundle_identifier | Yes |  |

## Request Body

Array of custom scan expressions to add.

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Add custom scan expressions for Content Scanning. |
| 4XX | List existing Content Scan custom scan expressions failure response. |

**Success Response Schema:**

[waf-product-api-bundle_response-custom-scan-collection](../schemas/waf-product-api-bundle/waf-product-api-bundle-response-custom-scan-collection.md)

## Security

- **api_email**
- **api_key**
- **api_token**

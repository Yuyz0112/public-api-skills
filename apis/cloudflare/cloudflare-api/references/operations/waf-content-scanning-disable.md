# POST /zones/{zone_id}/content-upload-scan/disable

**Resource:** [Content Scanning](../resources/Content-Scanning.md)
**Disable Content Scanning**
**Operation ID:** `waf-content-scanning-disable`

Disable Content Scanning.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | waf-product-api-bundle_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Disable Content Scanning response. |
| 4XX | Disable Content Scanning failure response. |

**Success Response Schema:**

[waf-product-api-bundle_schemas-api-response-common](../schemas/waf-product-api-bundle/waf-product-api-bundle-schemas-api-response-common.md)

## Security

- **api_email**
- **api_key**
- **api_token**

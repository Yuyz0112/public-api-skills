# GET /zones/{zone_id}/content-upload-scan/settings

**Resource:** [Content Scanning](../resources/Content-Scanning.md)
**Get Content Scanning Status**
**Operation ID:** `waf-content-scanning-get-status`

Retrieve the current status of Content Scanning.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | waf-product-api-bundle_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get Content Scanning status response. |
| 4XX | Get Content Scanning status failure response. |

**Success Response Schema:**

[waf-product-api-bundle_schemas-response-status](../schemas/waf-product-api-bundle/waf-product-api-bundle-schemas-response-status.md)

## Security

- **api_email**
- **api_key**
- **api_token**

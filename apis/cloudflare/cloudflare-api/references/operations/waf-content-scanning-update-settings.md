# PUT /zones/{zone_id}/content-upload-scan/settings

**Resource:** [Content Scanning](../resources/Content-Scanning.md)
**Update Content Scanning Status**
**Operation ID:** `waf-content-scanning-update-settings`

Update the Content Scanning status.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | waf-product-api-bundle_identifier | Yes |  |

## Request Body

Content Scanning settings to update.

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Update Content Scanning settings response. |
| 4XX | Update Content Scanning settings failure response. |

**Success Response Schema:**

[waf-product-api-bundle_schemas-response-status](../schemas/waf-product-api-bundle/waf-product-api-bundle-schemas-response-status.md)

## Security

- **api_email**
- **api_key**
- **api_token**

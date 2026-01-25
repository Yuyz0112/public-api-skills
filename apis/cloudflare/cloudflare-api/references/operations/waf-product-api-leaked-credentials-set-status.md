# POST /zones/{zone_id}/leaked-credential-checks

**Resource:** [Leaked Credential Checks](../resources/Leaked-Credential-Checks.md)
**Set Leaked Credential Checks Status**
**Operation ID:** `waf-product-api-leaked-credentials-set-status`

Updates the current status of Leaked Credential Checks.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | waf-product-api-bundle_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [waf-product-api-bundle_status](../schemas/waf-product-api-bundle/waf-product-api-bundle-status.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Set Leaked Credential Checks status response. |
| 4XX | Set Leaked Credential Checks status failure response. |

**Success Response Schema:**

[waf-product-api-bundle_response-status](../schemas/waf-product-api-bundle/waf-product-api-bundle-response-status.md)

## Security

- **api_email**
- **api_key**
- **api_token**

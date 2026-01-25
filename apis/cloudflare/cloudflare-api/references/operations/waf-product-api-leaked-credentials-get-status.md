# GET /zones/{zone_id}/leaked-credential-checks

**Resource:** [Leaked Credential Checks](../resources/Leaked-Credential-Checks.md)
**Get Leaked Credential Checks Status**
**Operation ID:** `waf-product-api-leaked-credentials-get-status`

Retrieves the current status of Leaked Credential Checks.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | waf-product-api-bundle_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get Leaked Credential Checks status response. |
| 4XX | Get Leaked Credential Checks status failure response. |

**Success Response Schema:**

[waf-product-api-bundle_response-status](../schemas/waf-product-api-bundle/waf-product-api-bundle-response-status.md)

## Security

- **api_email**
- **api_key**
- **api_token**

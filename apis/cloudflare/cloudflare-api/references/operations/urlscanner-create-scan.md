# POST /accounts/{account_id}/urlscanner/scan

**Resource:** [URL Scanner (Deprecated)](../resources/URL-Scanner-Deprecated.md)
**Create URL Scan**
**Operation ID:** `urlscanner-create-scan`
⚠️ **Deprecated**

Submit a URL to scan. You can also set some options, like the visibility level and custom headers. Check limits at https://developers.cloudflare.com/security-center/investigate/scan-limits/.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | string | Yes | Account ID. |

## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Scan request accepted successfully. |
| 400 | Invalid params. |
| 409 | Scan request denied: hostname was recently scanned. |
| 429 | Scan request denied: rate limited. |

## Security

- **api_token**
- **api_email**
- **api_key**

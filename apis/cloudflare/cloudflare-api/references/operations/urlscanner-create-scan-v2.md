# POST /accounts/{account_id}/urlscanner/v2/scan

**Resource:** [URL Scanner](../resources/URL-Scanner.md)
**Create URL Scan**
**Operation ID:** `urlscanner-create-scan-v2`

Submit a URL to scan. Check limits at https://developers.cloudflare.com/security-center/investigate/scan-limits/.

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
| 400 | Invalid input. |
| 409 | Scan request denied: hostname was recently scanned. |
| 429 | Scan request denied: rate limited. |

## Security

- **api_token**
- **api_email**
- **api_key**

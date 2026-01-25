# POST /accounts/{account_id}/urlscanner/v2/bulk

**Resource:** [URL Scanner](../resources/URL-Scanner.md)
**Bulk create URL Scans**
**Operation ID:** `urlscanner-create-scan-bulk-v2`

Submit URLs to scan. Check limits at https://developers.cloudflare.com/security-center/investigate/scan-limits/ and take into account scans submitted in bulk have lower priority and may take longer to finish.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | string | Yes | Account ID. |

## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Scan bulk request accepted successfully. |
| 400 | Invalid input. |
| 429 | Scan request denied: rate limited. |

## Security

- **api_token**
- **api_email**
- **api_key**

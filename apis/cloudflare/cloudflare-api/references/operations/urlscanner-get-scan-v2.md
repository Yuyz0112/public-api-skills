# GET /accounts/{account_id}/urlscanner/v2/result/{scan_id}

**Resource:** [URL Scanner](../resources/URL-Scanner.md)
**Get URL scan**
**Operation ID:** `urlscanner-get-scan-v2`

Get URL scan by uuid

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `scan_id` | path | string (uuid) | Yes | Scan UUID. |
| `account_id` | path | string | Yes | Account ID. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Scan has finished. It may or may not have been successful. |
| 400 | Invalid input. |
| 404 | Scan not found or in progress. |

## Security

- **api_token**
- **api_email**
- **api_key**

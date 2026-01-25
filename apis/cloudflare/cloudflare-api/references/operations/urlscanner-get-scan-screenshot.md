# GET /accounts/{account_id}/urlscanner/scan/{scan_id}/screenshot

**Resource:** [URL Scanner (Deprecated)](../resources/URL-Scanner-Deprecated.md)
**Get screenshot**
**Operation ID:** `urlscanner-get-scan-screenshot`
⚠️ **Deprecated**

Get scan's screenshot by resolution (desktop/mobile/tablet).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `scan_id` | path | string (uuid) | Yes | Scan UUID. |
| `account_id` | path | string | Yes | Account ID. |
| `resolution` | query | enum: desktop, mobile, tablet | No | Target device type. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returns the scan's requested screenshot. |
| 202 | Scan is in progress. Check current status in `result.scan.task.status`. Possible statuses: `Queued`,`InProgress`,`InPostProcessing`,`Finished`. |
| 400 | Invalid params. |
| 404 | Scan not found. |

## Security

- **api_token**
- **api_email**
- **api_key**

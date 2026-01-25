# GET /accounts/{account_id}/urlscanner/scan/{scan_id}

**Resource:** [URL Scanner (Deprecated)](../resources/URL-Scanner-Deprecated.md)
**Get URL scan**
**Operation ID:** `urlscanner-get-scan`
⚠️ **Deprecated**

Get URL scan by uuid

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `scan_id` | path | string (uuid) | Yes | Scan UUID. |
| `account_id` | path | string | Yes | Account ID. |
| `full` | query | boolean | No | Whether to return full report (scan summary and network log). |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Scan has finished. It may or may not have been successful. |
| 202 | Scan is in progress. Check current status in `result.scan.task.status`. Possible statuses: `Queued`,`InProgress`,`InPostProcessing`,`Finished`. |
| 400 | Invalid params. |
| 404 | Scan not found. |

## Security

- **api_token**
- **api_email**
- **api_key**

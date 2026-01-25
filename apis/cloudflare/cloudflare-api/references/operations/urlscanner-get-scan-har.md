# GET /accounts/{account_id}/urlscanner/scan/{scan_id}/har

**Resource:** [URL Scanner (Deprecated)](../resources/URL-Scanner-Deprecated.md)
**Get URL scan's HAR**
**Operation ID:** `urlscanner-get-scan-har`
⚠️ **Deprecated**

Get a URL scan's HAR file. See HAR spec at http://www.softwareishard.com/blog/har-12-spec/.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `scan_id` | path | string (uuid) | Yes | Scan UUID. |
| `account_id` | path | string | Yes | Account ID. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returns the scan's har. |
| 202 | Scan is in progress. Check current status in `result.scan.task.status`. Possible statuses: `Queued`,`InProgress`,`InPostProcessing`,`Finished`. |
| 400 | Invalid params. |
| 404 | Scan not found. |

## Security

- **api_token**
- **api_email**
- **api_key**

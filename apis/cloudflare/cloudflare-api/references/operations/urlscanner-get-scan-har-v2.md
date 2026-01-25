# GET /accounts/{account_id}/urlscanner/v2/har/{scan_id}

**Resource:** [URL Scanner](../resources/URL-Scanner.md)
**Get URL scan's HAR**
**Operation ID:** `urlscanner-get-scan-har-v2`

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
| 400 | Invalid input. |
| 404 | Scan not found or in progress. |

## Security

- **api_token**
- **api_email**
- **api_key**

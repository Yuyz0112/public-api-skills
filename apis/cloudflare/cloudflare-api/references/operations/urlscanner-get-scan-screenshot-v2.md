# GET /accounts/{account_id}/urlscanner/v2/screenshots/{scan_id}.png

**Resource:** [URL Scanner](../resources/URL-Scanner.md)
**Get screenshot**
**Operation ID:** `urlscanner-get-scan-screenshot-v2`

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
| 400 | Invalid input. |
| 404 | Scan not found or in progress. |

## Security

- **api_token**
- **api_email**
- **api_key**

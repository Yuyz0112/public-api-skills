# GET /accounts/{account_id}/urlscanner/v2/dom/{scan_id}

**Resource:** [URL Scanner](../resources/URL-Scanner.md)
**Get URL scan's DOM**
**Operation ID:** `urlscanner-get-scan-dom-v2`

Returns a plain text response, with the scan's DOM content as rendered by Chrome.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `scan_id` | path | string (uuid) | Yes | Scan UUID. |
| `account_id` | path | string | Yes | Account ID. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returns a plain text response, with the scan's DOM content as rendered by Chrome. |
| 400 | Invalid input. |
| 404 | Scan not found or in progress. |

## Security

- **api_token**
- **api_email**
- **api_key**

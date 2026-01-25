# GET /accounts/{account_id}/dlp/payload_log

**Resource:** [DLP Settings](../resources/DLP-Settings.md)
**Get payload log settings**
**Operation ID:** `dlp-payload-log-get`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | string | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Payload log settings. |
| 4XX | Failed to get payload log settings. |

## Security

- **api_email**
- **api_key**
- **api_token**

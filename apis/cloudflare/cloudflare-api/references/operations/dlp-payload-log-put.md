# PUT /accounts/{account_id}/dlp/payload_log

**Resource:** [DLP Settings](../resources/DLP-Settings.md)
**Set payload log settings**
**Operation ID:** `dlp-payload-log-put`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | string | Yes |  |

## Request Body

New payload log settings.

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [dlp_PayloadLogSettingUpdate](../schemas/dlp/dlp-PayloadLogSettingUpdate.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Payload log settings. |
| 4XX | Failed to set payload log settings. |

## Security

- **api_email**
- **api_key**
- **api_token**

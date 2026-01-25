# GET /accounts/{account_id}/dlp/limits

**Resource:** [DLP Settings](../resources/DLP-Settings.md)
**Fetch limits associated with DLP for account**
**Operation ID:** `dlp-limits-get`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | string | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Limits retrieved successfully. |
| 4XX | Limits get failed. |

## Security

- **api_email**
- **api_key**
- **api_token**

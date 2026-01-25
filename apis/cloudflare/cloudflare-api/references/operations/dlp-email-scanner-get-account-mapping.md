# GET /accounts/{account_id}/dlp/email/account_mapping

**Resource:** [DLP Email](../resources/DLP-Email.md)
**Get mapping**
**Operation ID:** `dlp-email-scanner-get-account-mapping`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | string | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get Email Scanner Account Mapping response. |
| 4XX | Get Email Scanner Account Mapping failure response. |

## Security

- **api_email**
- **api_key**
- **api_token**

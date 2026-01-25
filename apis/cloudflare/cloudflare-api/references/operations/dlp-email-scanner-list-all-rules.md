# GET /accounts/{account_id}/dlp/email/rules

**Resource:** [DLP Email](../resources/DLP-Email.md)
**List all email scanner rules**
**Operation ID:** `dlp-email-scanner-list-all-rules`

Lists all email scanner rules for an account.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | string | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List all email scanner rules response. |
| 4XX | List all email scanner rules failure response. |

## Security

- **api_email**
- **api_key**
- **api_token**

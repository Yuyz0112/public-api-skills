# POST /accounts/{account_id}/dlp/email/rules

**Resource:** [DLP Email](../resources/DLP-Email.md)
**Create email scanner rule**
**Operation ID:** `dlp-email-scanner-create-rule`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | string | Yes |  |

## Request Body

Rule description.

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [dlp_CreateEmailRule](../schemas/dlp/dlp-CreateEmailRule.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | New Email Scanner Rule response. |
| 4XX | New Email Scanner Rule failure response. |

## Security

- **api_email**
- **api_key**
- **api_token**

# PUT /accounts/{account_id}/dlp/email/rules/{rule_id}

**Resource:** [DLP Email](../resources/DLP-Email.md)
**Update email scanner rule**
**Operation ID:** `dlp-email-scanner-update-rule`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | string | Yes |  |
| `rule_id` | path | string (uuid) | Yes |  |

## Request Body

Rule description.

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [dlp_CreateEmailRule](../schemas/dlp/dlp-CreateEmailRule.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Update Email Scanner Rule response. |
| 4XX | Update Email Scanner Rule failure response. |

## Security

- **api_email**
- **api_key**
- **api_token**

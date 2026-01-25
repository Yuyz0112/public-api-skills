# PATCH /accounts/{account_id}/dlp/email/rules

**Resource:** [DLP Email](../resources/DLP-Email.md)
**Update email scanner rule priorities**
**Operation ID:** `dlp-email-scanner-update-rule-priorities`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | string | Yes |  |

## Request Body

Rule priorities.

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [dlp_UpdateEmailRulePriorities](../schemas/dlp/dlp-UpdateEmailRulePriorities.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Update Email Scanner Rule priorities response. |
| 4XX | Update Email Scanner Rule priorities failure response. |

## Security

- **api_email**
- **api_key**
- **api_token**

# POST /accounts/{account_id}/email-security/investigate/preview

**Resource:** [Email Security](../resources/Email-Security.md)
**Preview for non-detection messages**
**Operation ID:** `email_security_post_preview`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | email-security_AccountId | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 |  |
| 4XX | (reference) |

## Security

- **api_email**
- **api_key**

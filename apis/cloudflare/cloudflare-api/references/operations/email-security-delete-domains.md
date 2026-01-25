# DELETE /accounts/{account_id}/email-security/settings/domains

**Resource:** [Email Security Settings](../resources/Email-Security-Settings.md)
**Unprotect multiple email domains**
**Operation ID:** `email_security_delete_domains`

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

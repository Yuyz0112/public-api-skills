# POST /accounts/{account_id}/email-security/settings/impersonation_registry

**Resource:** [Email Security Settings](../resources/Email-Security-Settings.md)
**Create an entry in impersonation registry**
**Operation ID:** `email_security_create_display_name`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | email-security_AccountId | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [email-security_CreateDisplayName](../schemas/email-security/email-security-CreateDisplayName.md)

## Responses

| Status | Description |
|--------|-------------|
| 201 |  |
| 4XX | (reference) |

## Security

- **api_email**
- **api_key**

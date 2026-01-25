# PATCH /accounts/{account_id}/email-security/settings/impersonation_registry/{display_name_id}

**Resource:** [Email Security Settings](../resources/Email-Security-Settings.md)
**Update an entry in impersonation registry**
**Operation ID:** `email_security_update_display_name`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | email-security_AccountId | Yes |  |
| `display_name_id` | path | integer (int32) | Yes |  |

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

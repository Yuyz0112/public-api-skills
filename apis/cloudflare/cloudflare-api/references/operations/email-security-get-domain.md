# GET /accounts/{account_id}/email-security/settings/domains/{domain_id}

**Resource:** [Email Security Settings](../resources/Email-Security-Settings.md)
**Get an email domain**
**Operation ID:** `email_security_get_domain`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | email-security_AccountId | Yes |  |
| `domain_id` | path | integer (int32) | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 |  |
| 4XX | (reference) |

## Security

- **api_email**
- **api_key**

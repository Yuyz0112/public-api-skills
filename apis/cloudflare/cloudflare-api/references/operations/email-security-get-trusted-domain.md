# GET /accounts/{account_id}/email-security/settings/trusted_domains/{trusted_domain_id}

**Resource:** [Email Security Settings](../resources/Email-Security-Settings.md)
**Get a trusted email domain**
**Operation ID:** `email_security_get_trusted_domain`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | email-security_AccountId | Yes |  |
| `trusted_domain_id` | path | email-security_TrustedDomainId | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 |  |
| 4XX | (reference) |

## Security

- **api_email**
- **api_key**

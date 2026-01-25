# POST /accounts/{account_id}/email-security/settings/sending_domain_restrictions/batch

**Resource:** [Email Security Settings](../resources/Email-Security-Settings.md)
**Batch Sending Domain Restrictions**
**Operation ID:** `email_security_batch_sending_domain_restrictions`

Send a Batch of `sending_domain_restrictions` API calls to be executed together.

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

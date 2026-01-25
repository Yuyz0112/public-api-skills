# POST /accounts/{account_id}/email-security/settings/trusted_domains/batch

**Resource:** [Email Security Settings](../resources/Email-Security-Settings.md)
**Batch Trusted Domains**
**Operation ID:** `email_security_batch_trusted_domains`

Send a Batch of Trusted Domains API calls to be executed together.

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

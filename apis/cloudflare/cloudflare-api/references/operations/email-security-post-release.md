# POST /accounts/{account_id}/email-security/investigate/release

**Resource:** [Email Security](../resources/Email-Security.md)
**Release messages from quarantine**
**Operation ID:** `email_security_post_release`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | email-security_AccountId | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** Array of [email-security_PostfixId](../schemas/email-security/email-security-PostfixId.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 |  |
| 4XX | (reference) |

## Security

- **api_email**
- **api_key**

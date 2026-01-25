# POST /accounts/{account_id}/email-security/settings/allow_policies

**Resource:** [Email Security Settings](../resources/Email-Security-Settings.md)
**Create an email allow policy**
**Operation ID:** `email_security_create_allow_policy`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | email-security_AccountId | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [email-security_CreateAllowPolicy](../schemas/email-security/email-security-CreateAllowPolicy.md)

## Responses

| Status | Description |
|--------|-------------|
| 201 | Contains the newly created policy. |
| 4XX | (reference) |

## Security

- **api_email**
- **api_key**

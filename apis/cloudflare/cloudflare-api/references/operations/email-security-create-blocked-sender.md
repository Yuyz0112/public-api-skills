# POST /accounts/{account_id}/email-security/settings/block_senders

**Resource:** [Email Security Settings](../resources/Email-Security-Settings.md)
**Create a blocked email sender**
**Operation ID:** `email_security_create_blocked_sender`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | email-security_AccountId | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [email-security_CreateBlockedSender](../schemas/email-security/email-security-CreateBlockedSender.md)

## Responses

| Status | Description |
|--------|-------------|
| 201 | Contains the newly created pattern. |
| 4XX | (reference) |

## Security

- **api_email**
- **api_key**

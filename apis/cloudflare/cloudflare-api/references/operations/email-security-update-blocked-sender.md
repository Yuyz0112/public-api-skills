# PATCH /accounts/{account_id}/email-security/settings/block_senders/{pattern_id}

**Resource:** [Email Security Settings](../resources/Email-Security-Settings.md)
**Update a blocked email sender**
**Operation ID:** `email_security_update_blocked_sender`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | email-security_AccountId | Yes |  |
| `pattern_id` | path | email-security_BlockedSenderId | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [email-security_UpdateBlockedSender](../schemas/email-security/email-security-UpdateBlockedSender.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 |  |
| 4XX | (reference) |

## Security

- **api_email**
- **api_key**

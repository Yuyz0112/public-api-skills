# DELETE /accounts/{account_id}/email-security/settings/block_senders/{pattern_id}

**Resource:** [Email Security Settings](../resources/Email-Security-Settings.md)
**Delete a blocked email sender**
**Operation ID:** `email_security_delete_blocked_sender`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | email-security_AccountId | Yes |  |
| `pattern_id` | path | email-security_BlockedSenderId | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 |  |
| 4XX | (reference) |

## Security

- **api_email**
- **api_key**

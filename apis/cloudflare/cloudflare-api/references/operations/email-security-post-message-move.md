# POST /accounts/{account_id}/email-security/investigate/{postfix_id}/move

**Resource:** [Email Security](../resources/Email-Security.md)
**Move a message**
**Operation ID:** `email_security_post_message_move`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | email-security_AccountId | Yes |  |
| `postfix_id` | path | string | Yes |  |

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

# GET /accounts/{account_id}/email-security/investigate/{postfix_id}/preview

**Resource:** [Email Security](../resources/Email-Security.md)
**Get email preview**
**Operation ID:** `email_security_get_message_preview`

Returns a preview of the message body as a base64 encoded PNG image for non-benign messages.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | email-security_AccountId | Yes |  |
| `postfix_id` | path | string | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Contains a preview of the email. |
| 4XX | (reference) |

## Security

- **api_email**
- **api_key**

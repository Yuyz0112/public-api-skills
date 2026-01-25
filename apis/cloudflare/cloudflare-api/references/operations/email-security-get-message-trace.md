# GET /accounts/{account_id}/email-security/investigate/{postfix_id}/trace

**Resource:** [Email Security](../resources/Email-Security.md)
**Get email trace**
**Operation ID:** `email_security_get_message_trace`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | email-security_AccountId | Yes |  |
| `postfix_id` | path | string | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Contains the email trace. |
| 4XX | (reference) |

## Security

- **api_email**
- **api_key**

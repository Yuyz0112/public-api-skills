# GET /accounts/{account_id}/email-security/investigate/{postfix_id}/raw

**Resource:** [Email Security](../resources/Email-Security.md)
**Get raw email content**
**Operation ID:** `email_security_get_message_raw`

Returns the raw eml of any non-benign message.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | email-security_AccountId | Yes |  |
| `postfix_id` | path | string | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Contains the raw content of the email. |
| 4XX | (reference) |

## Security

- **api_email**
- **api_key**

# GET /accounts/{account_id}/email-security/investigate/{postfix_id}

**Resource:** [Email Security](../resources/Email-Security.md)
**Get message details**
**Operation ID:** `email_security_get_message`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | email-security_AccountId | Yes |  |
| `postfix_id` | path | string | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Contains the email message details. |
| 4XX | (reference) |

## Security

- **api_email**
- **api_key**

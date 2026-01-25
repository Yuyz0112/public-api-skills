# POST /accounts/{account_id}/email-security/investigate/{postfix_id}/reclassify

**Resource:** [Email Security](../resources/Email-Security.md)
**Change email classfication**
**Operation ID:** `email_security_post_reclassify`

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
| 202 |  |
| 4XX | (reference) |

## Security

- **api_email**
- **api_key**

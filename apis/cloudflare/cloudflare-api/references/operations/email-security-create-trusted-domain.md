# POST /accounts/{account_id}/email-security/settings/trusted_domains

**Resource:** [Email Security Settings](../resources/Email-Security-Settings.md)
**Create a trusted email domain**
**Operation ID:** `email_security_create_trusted_domain`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | email-security_AccountId | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Contains the new trusted domain in the shape of the request body. |
| 4XX | (reference) |

## Security

- **api_email**
- **api_key**

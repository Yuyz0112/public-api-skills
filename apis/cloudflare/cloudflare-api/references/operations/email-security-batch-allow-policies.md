# POST /accounts/{account_id}/email-security/settings/allow_policies/batch

**Resource:** [Email Security Settings](../resources/Email-Security-Settings.md)
**Batch Allow Policies**
**Operation ID:** `email_security_batch_allow_policies`

Send a Batch of Allow Policies API calls to be executed together.

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
| 200 |  |
| 4XX | (reference) |

## Security

- **api_email**
- **api_key**

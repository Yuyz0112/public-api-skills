# POST /accounts/{account_id}/email-security/settings/block_senders/batch

**Resource:** [Email Security Settings](../resources/Email-Security-Settings.md)
**Batch Block Senders**
**Operation ID:** `email_security_batch_blocked_senders`

Send a Batch of Block Senders API calls to be executed together.

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

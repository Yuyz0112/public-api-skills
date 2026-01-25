# PUT /accounts/{account_id}/workers/account-settings

**Resource:** [Worker Account Settings](../resources/Worker-Account-Settings.md)
**Create Worker Account Settings**
**Operation ID:** `worker-account-settings-create-worker-account-settings`

Creates Worker account settings for an account.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | workers_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [workers_account-settings](../schemas/workers/workers-account-settings.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Create Worker Account Settings response. |
| 4XX | Create Worker Account Settings response failure. |

## Security

- **api_token**
- **api_email**
- **api_key**

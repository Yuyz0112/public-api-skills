# GET /accounts/{account_id}/workers/account-settings

**Resource:** [Worker Account Settings](../resources/Worker-Account-Settings.md)
**Fetch Worker Account Settings**
**Operation ID:** `worker-account-settings-fetch-worker-account-settings`

Fetches Worker account settings for an account.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | workers_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Fetch Worker Account Settings response. |
| 4XX | Fetch Worker Account Settings response failure. |

## Security

- **api_token**
- **api_email**
- **api_key**

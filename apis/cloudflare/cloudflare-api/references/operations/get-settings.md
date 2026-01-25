# GET /accounts/{account_id}/cni/settings

**Resource:** [Settings](../resources/Settings.md)
**Get the current settings for the active account**
**Operation ID:** `get_settings`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | string | Yes | Account tag to retrieve settings for |

## Responses

| Status | Description |
|--------|-------------|
| 200 | The active account settings values |
| 400 | Bad request |
| 404 | Account not found |
| 500 | Internal server error |

**Success Response Schema:**

[nsc_Settings](../schemas/nsc/nsc-Settings.md)

## Security

- **api_email**
- **api_key**
- **api_token**

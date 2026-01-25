# GET /accounts/{account_id}/devices/settings

**Resource:** [Zero Trust accounts](../resources/Zero-Trust-accounts.md)
**Get device settings for a Zero Trust account**
**Operation ID:** `zero-trust-accounts-get-device-settings-for-zero-trust-account`

Describes the current device settings for a Zero Trust account.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | teams-devices_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get device settings for a Zero Trust account response. |
| 4XX | Get device settings for a Zero Trust account response failure. |

**Success Response Schema:**

[teams-devices_zero-trust-account-device-settings-response](../schemas/teams-devices/teams-devices-zero-trust-account-device-settings-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**

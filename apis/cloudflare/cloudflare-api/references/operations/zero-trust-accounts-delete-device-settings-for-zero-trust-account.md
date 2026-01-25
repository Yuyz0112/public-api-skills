# DELETE /accounts/{account_id}/devices/settings

**Resource:** [Zero Trust accounts](../resources/Zero-Trust-accounts.md)
**Reset device settings for a Zero Trust account with defaults. This turns off all proxying.**
**Operation ID:** `zero-trust-accounts-delete-device-settings-for-zero-trust-account`

Resets the current device settings for a Zero Trust account.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | teams-devices_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Reset response for device settings for a Zero Trust account. |
| 4XX | Reset failure response device settings for a Zero Trust account. |

**Success Response Schema:**

[teams-devices_zero-trust-account-device-settings-response](../schemas/teams-devices/teams-devices-zero-trust-account-device-settings-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**

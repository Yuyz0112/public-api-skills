# GET /accounts/{account_id}/devices/policy

**Resource:** [Devices](../resources/Devices.md)
**Get the default device settings profile**
**Operation ID:** `devices-get-default-device-settings-policy`

Fetches the default device settings profile for an account.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | teams-devices_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get the default device settings profile response. |
| 4XX | Get the default device settings profile response failure. |

**Success Response Schema:**

[teams-devices_default_device_settings_response](../schemas/teams-devices/teams-devices-default-device-settings-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**

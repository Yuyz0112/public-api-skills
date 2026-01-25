# PATCH /accounts/{account_id}/devices/policy

**Resource:** [Devices](../resources/Devices.md)
**Update the default device settings profile**
**Operation ID:** `devices-update-default-device-settings-policy`

Updates the default device settings profile for an account.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | teams-devices_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Update the default device settings profile response. |
| 4XX | Update the default device settings profile response failure. |

**Success Response Schema:**

[teams-devices_default_device_settings_response](../schemas/teams-devices/teams-devices-default-device-settings-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**

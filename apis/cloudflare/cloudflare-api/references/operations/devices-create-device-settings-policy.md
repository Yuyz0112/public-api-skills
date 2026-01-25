# POST /accounts/{account_id}/devices/policy

**Resource:** [Devices](../resources/Devices.md)
**Create a device settings profile**
**Operation ID:** `devices-create-device-settings-policy`

Creates a device settings profile to be applied to certain devices matching the criteria.

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
| 200 | Create a device settings profile response. |
| 4XX | Create a device settings profile response failure. |

**Success Response Schema:**

[teams-devices_device_settings_response](../schemas/teams-devices/teams-devices-device-settings-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**

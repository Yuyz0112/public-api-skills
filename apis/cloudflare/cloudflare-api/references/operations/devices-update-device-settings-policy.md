# PATCH /accounts/{account_id}/devices/policy/{policy_id}

**Resource:** [Devices](../resources/Devices.md)
**Update a device settings profile**
**Operation ID:** `devices-update-device-settings-policy`

Updates a configured device settings profile.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `policy_id` | path | teams-devices_schemas-uuid | Yes |  |
| `account_id` | path | teams-devices_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Update a device settings profile Policy response. |
| 4XX | Update a device settings profile Policy response failure. |

**Success Response Schema:**

[teams-devices_device_settings_response](../schemas/teams-devices/teams-devices-device-settings-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**

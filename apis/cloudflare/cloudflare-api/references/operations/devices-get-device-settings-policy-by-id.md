# GET /accounts/{account_id}/devices/policy/{policy_id}

**Resource:** [Devices](../resources/Devices.md)
**Get device settings profile by ID**
**Operation ID:** `devices-get-device-settings-policy-by-id`

Fetches a device settings profile by ID.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `policy_id` | path | teams-devices_schemas-uuid | Yes |  |
| `account_id` | path | teams-devices_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get device settings profile by ID response. |
| 4XX | Get device settings profile by ID response failure. |

**Success Response Schema:**

[teams-devices_device_settings_response](../schemas/teams-devices/teams-devices-device-settings-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**

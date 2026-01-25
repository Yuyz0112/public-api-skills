# GET /accounts/{account_id}/devices/policies

**Resource:** [Devices](../resources/Devices.md)
**List device settings profiles**
**Operation ID:** `devices-list-device-settings-policies`

Fetches a list of the device settings profiles for an account.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | teams-devices_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List device settings profiles response. |
| 4XX | List device settings profiles response failure. |

**Success Response Schema:**

[teams-devices_device_settings_response_collection](../schemas/teams-devices/teams-devices-device-settings-response-collection.md)

## Security

- **api_email**
- **api_key**
- **api_token**

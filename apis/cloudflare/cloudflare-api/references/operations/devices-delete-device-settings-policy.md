# DELETE /accounts/{account_id}/devices/policy/{policy_id}

**Resource:** [Devices](../resources/Devices.md)
**Delete a device settings profile**
**Operation ID:** `devices-delete-device-settings-policy`

Deletes a device settings profile and fetches a list of the remaining profiles for an account.

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
| 200 | Delete a device settings profile response. |
| 4XX | Delete a device settings profile response failure. |

**Success Response Schema:**

[teams-devices_device_settings_response_collection](../schemas/teams-devices/teams-devices-device-settings-response-collection.md)

## Security

- **api_email**
- **api_key**
- **api_token**

# GET /accounts/{account_id}/devices/policy/{policy_id}/exclude

**Resource:** [Devices](../resources/Devices.md)
**Get the Split Tunnel exclude list for a device settings profile**
**Operation ID:** `devices-get-split-tunnel-exclude-list-for-a-device-settings-policy`

Fetches the list of routes excluded from the WARP client's tunnel for a specific device settings profile.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `policy_id` | path | teams-devices_schemas-uuid | Yes |  |
| `account_id` | path | teams-devices_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get the Split Tunnel exclude list for a device settings profile response. |
| 4XX | Get the Split Tunnel exclude list for a device settings profile response failure. |

**Success Response Schema:**

[teams-devices_split_tunnel_response_collection](../schemas/teams-devices/teams-devices-split-tunnel-response-collection.md)

## Security

- **api_email**
- **api_key**
- **api_token**

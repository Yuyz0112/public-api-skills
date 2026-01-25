# PUT /accounts/{account_id}/devices/policy/exclude

**Resource:** [Devices](../resources/Devices.md)
**Set the Split Tunnel exclude list**
**Operation ID:** `devices-set-split-tunnel-exclude-list`

Sets the list of routes excluded from the WARP client's tunnel.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | teams-devices_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** Array of [teams-devices_split_tunnel](../schemas/teams-devices/teams-devices-split-tunnel.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Set the Split Tunnel exclude list response. |
| 4XX | Set the Split Tunnel exclude list response failure. |

**Success Response Schema:**

[teams-devices_split_tunnel_response_collection](../schemas/teams-devices/teams-devices-split-tunnel-response-collection.md)

## Security

- **api_email**
- **api_key**
- **api_token**

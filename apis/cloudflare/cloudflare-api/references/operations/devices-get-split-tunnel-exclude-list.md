# GET /accounts/{account_id}/devices/policy/exclude

**Resource:** [Devices](../resources/Devices.md)
**Get the Split Tunnel exclude list**
**Operation ID:** `devices-get-split-tunnel-exclude-list`

Fetches the list of routes excluded from the WARP client's tunnel.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | teams-devices_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get the Split Tunnel exclude list response. |
| 4XX | Get the Split Tunnel exclude list response failure. |

**Success Response Schema:**

[teams-devices_split_tunnel_response_collection](../schemas/teams-devices/teams-devices-split-tunnel-response-collection.md)

## Security

- **api_email**
- **api_key**
- **api_token**

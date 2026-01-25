# GET /accounts/{account_id}/devices/policy/include

**Resource:** [Devices](../resources/Devices.md)
**Get the Split Tunnel include list**
**Operation ID:** `devices-get-split-tunnel-include-list`

Fetches the list of routes included in the WARP client's tunnel.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | teams-devices_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get the Split Tunnel include list response. |
| 4XX | Get the Split Tunnel include list response failure. |

**Success Response Schema:**

[teams-devices_split_tunnel_include_response_collection](../schemas/teams-devices/teams-devices-split-tunnel-include-response-collection.md)

## Security

- **api_email**
- **api_key**
- **api_token**

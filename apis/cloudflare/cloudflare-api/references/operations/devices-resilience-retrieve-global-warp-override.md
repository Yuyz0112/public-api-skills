# GET /accounts/{account_id}/devices/resilience/disconnect

**Resource:** [Devices Resilience](../resources/Devices-Resilience.md)
**Retrieve Global WARP override state**
**Operation ID:** `devices-resilience-retrieve-global-warp-override`

Fetch the Global WARP override state.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | teams-devices_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Fetch Global WARP override state response. |
| 4XX | Fetch Global WARP override state failure. |

**Success Response Schema:**

[teams-devices_global_warp_override_response](../schemas/teams-devices/teams-devices-global-warp-override-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**

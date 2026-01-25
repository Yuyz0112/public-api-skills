# POST /accounts/{account_id}/devices/resilience/disconnect

**Resource:** [Devices Resilience](../resources/Devices-Resilience.md)
**Set Global WARP override state**
**Operation ID:** `devices-resilience-set-global-warp-override`

Sets the Global WARP override state.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | teams-devices_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [teams-devices_global_warp_override_request](../schemas/teams-devices/teams-devices-global-warp-override-request.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Set Global WARP override state response. |
| 4XX | Set Global WARP override state response failure. |

**Success Response Schema:**

[teams-devices_global_warp_override_response](../schemas/teams-devices/teams-devices-global-warp-override-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**

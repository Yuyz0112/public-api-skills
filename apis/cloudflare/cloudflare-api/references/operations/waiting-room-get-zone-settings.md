# GET /zones/{zone_id}/waiting_rooms/settings

**Resource:** [Waiting Room](../resources/Waiting-Room.md)
**Get zone-level Waiting Room settings**
**Operation ID:** `waiting-room-get-zone-settings`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | waitingroom_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | The current zone-level Waiting Room settings |
| 4XX | The current zone-level Waiting Room settings response failure |

**Success Response Schema:**

[waitingroom_zone_settings_response](../schemas/waitingroom/waitingroom-zone-settings-response.md)

## Security

- **api_token**
- **api_email**
- **api_key**

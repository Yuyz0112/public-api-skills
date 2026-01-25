# PATCH /zones/{zone_id}/waiting_rooms/settings

**Resource:** [Waiting Room](../resources/Waiting-Room.md)
**Patch zone-level Waiting Room settings**
**Operation ID:** `waiting-room-patch-zone-settings`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | waitingroom_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [waitingroom_zone_settings](../schemas/waitingroom/waitingroom-zone-settings.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | The updated zone-level Waiting Room settings |
| 4XX | The zone-level Waiting Room settings response failure |

**Success Response Schema:**

[waitingroom_zone_settings_response](../schemas/waitingroom/waitingroom-zone-settings-response.md)

## Security

- **api_token**
- **api_email**
- **api_key**

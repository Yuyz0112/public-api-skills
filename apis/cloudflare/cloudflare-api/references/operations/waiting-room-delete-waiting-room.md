# DELETE /zones/{zone_id}/waiting_rooms/{waiting_room_id}

**Resource:** [Waiting Room](../resources/Waiting-Room.md)
**Delete waiting room**
**Operation ID:** `waiting-room-delete-waiting-room`

Deletes a waiting room.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `waiting_room_id` | path | waitingroom_waiting_room_id | Yes |  |
| `zone_id` | path | waitingroom_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Delete waiting room response |
| 4XX | Delete waiting room response failure |

**Success Response Schema:**

[waitingroom_waiting_room_id_response](../schemas/waitingroom/waitingroom-waiting-room-id-response.md)

## Security

- **api_token**
- **api_email**
- **api_key**

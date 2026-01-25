# DELETE /zones/{zone_id}/waiting_rooms/{waiting_room_id}/events/{event_id}

**Resource:** [Waiting Room](../resources/Waiting-Room.md)
**Delete event**
**Operation ID:** `waiting-room-delete-event`

Deletes an event for a waiting room.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `event_id` | path | waitingroom_event_id | Yes |  |
| `waiting_room_id` | path | waitingroom_waiting_room_id | Yes |  |
| `zone_id` | path | waitingroom_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Delete event response |
| 4XX | Delete event response failure |

**Success Response Schema:**

[waitingroom_event_id_response](../schemas/waitingroom/waitingroom-event-id-response.md)

## Security

- **api_token**
- **api_email**
- **api_key**

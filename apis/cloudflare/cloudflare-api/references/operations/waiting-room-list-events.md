# GET /zones/{zone_id}/waiting_rooms/{waiting_room_id}/events

**Resource:** [Waiting Room](../resources/Waiting-Room.md)
**List events**
**Operation ID:** `waiting-room-list-events`

Lists events for a waiting room.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `waiting_room_id` | path | waitingroom_waiting_room_id | Yes |  |
| `zone_id` | path | waitingroom_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List events response |
| 4XX | List events response failure |

**Success Response Schema:**

[waitingroom_event_response_collection](../schemas/waitingroom/waitingroom-event-response-collection.md)

## Security

- **api_token**
- **api_email**
- **api_key**

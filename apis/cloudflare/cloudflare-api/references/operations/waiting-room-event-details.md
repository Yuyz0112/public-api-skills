# GET /zones/{zone_id}/waiting_rooms/{waiting_room_id}/events/{event_id}

**Resource:** [Waiting Room](../resources/Waiting-Room.md)
**Event details**
**Operation ID:** `waiting-room-event-details`

Fetches a single configured event for a waiting room.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `event_id` | path | waitingroom_event_id | Yes |  |
| `waiting_room_id` | path | waitingroom_waiting_room_id | Yes |  |
| `zone_id` | path | waitingroom_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Event details response |
| 4XX | Event details response failure |

**Success Response Schema:**

[waitingroom_event_response](../schemas/waitingroom/waitingroom-event-response.md)

## Security

- **api_token**
- **api_email**
- **api_key**

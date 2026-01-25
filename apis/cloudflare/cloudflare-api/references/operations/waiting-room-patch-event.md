# PATCH /zones/{zone_id}/waiting_rooms/{waiting_room_id}/events/{event_id}

**Resource:** [Waiting Room](../resources/Waiting-Room.md)
**Patch event**
**Operation ID:** `waiting-room-patch-event`

Patches a configured event for a waiting room.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `event_id` | path | waitingroom_event_id | Yes |  |
| `waiting_room_id` | path | waitingroom_waiting_room_id | Yes |  |
| `zone_id` | path | waitingroom_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [waitingroom_query_event](../schemas/waitingroom/waitingroom-query-event.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Patch event response |
| 4XX | Patch event response failure |

**Success Response Schema:**

[waitingroom_event_response](../schemas/waitingroom/waitingroom-event-response.md)

## Security

- **api_token**
- **api_email**
- **api_key**

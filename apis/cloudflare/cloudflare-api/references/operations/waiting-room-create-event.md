# POST /zones/{zone_id}/waiting_rooms/{waiting_room_id}/events

**Resource:** [Waiting Room](../resources/Waiting-Room.md)
**Create event**
**Operation ID:** `waiting-room-create-event`

Only available for the Waiting Room Advanced subscription. Creates an event for a waiting room. An event takes place during a specified period of time, temporarily changing the behavior of a waiting room. While the event is active, some of the properties in the event's configuration may either override or inherit from the waiting room's configuration. Note that events cannot overlap with each other, so only one event can be active at a time.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `waiting_room_id` | path | waitingroom_waiting_room_id | Yes |  |
| `zone_id` | path | waitingroom_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [waitingroom_query_event](../schemas/waitingroom/waitingroom-query-event.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Create event response |
| 4XX | Create event response failure |

**Success Response Schema:**

[waitingroom_event_response](../schemas/waitingroom/waitingroom-event-response.md)

## Security

- **api_token**
- **api_email**
- **api_key**

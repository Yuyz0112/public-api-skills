# GET /zones/{zone_id}/waiting_rooms/{waiting_room_id}/events/{event_id}/details

**Resource:** [Waiting Room](../resources/Waiting-Room.md)
**Preview active event details**
**Operation ID:** `waiting-room-preview-active-event-details`

Previews an event's configuration as if it was active. Inherited fields from the waiting room will be displayed with their current values.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `event_id` | path | waitingroom_event_id | Yes |  |
| `waiting_room_id` | path | waitingroom_waiting_room_id | Yes |  |
| `zone_id` | path | waitingroom_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Preview active event details response |
| 4XX | Preview active event details response failure |

**Success Response Schema:**

[waitingroom_event_details_response](../schemas/waitingroom/waitingroom-event-details-response.md)

## Security

- **api_token**
- **api_email**
- **api_key**

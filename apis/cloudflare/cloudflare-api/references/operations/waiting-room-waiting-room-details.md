# GET /zones/{zone_id}/waiting_rooms/{waiting_room_id}

**Resource:** [Waiting Room](../resources/Waiting-Room.md)
**Waiting room details**
**Operation ID:** `waiting-room-waiting-room-details`

Fetches a single configured waiting room.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `waiting_room_id` | path | waitingroom_waiting_room_id | Yes |  |
| `zone_id` | path | waitingroom_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Waiting room details response |
| 4XX | Waiting room details response failure |

**Success Response Schema:**

[waitingroom_single_response](../schemas/waitingroom/waitingroom-single-response.md)

## Security

- **api_token**
- **api_email**
- **api_key**

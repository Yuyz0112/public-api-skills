# PUT /zones/{zone_id}/waiting_rooms/{waiting_room_id}

**Resource:** [Waiting Room](../resources/Waiting-Room.md)
**Update waiting room**
**Operation ID:** `waiting-room-update-waiting-room`

Updates a configured waiting room.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `waiting_room_id` | path | waitingroom_waiting_room_id | Yes |  |
| `zone_id` | path | waitingroom_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [waitingroom_query_waitingroom](../schemas/waitingroom/waitingroom-query-waitingroom.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Update waiting room response |
| 4XX | Update waiting room response failure |

**Success Response Schema:**

[waitingroom_single_response](../schemas/waitingroom/waitingroom-single-response.md)

## Security

- **api_token**
- **api_email**
- **api_key**

# GET /zones/{zone_id}/waiting_rooms/{waiting_room_id}/rules

**Resource:** [Waiting Room](../resources/Waiting-Room.md)
**List Waiting Room Rules**
**Operation ID:** `waiting-room-list-waiting-room-rules`

Lists rules for a waiting room.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `waiting_room_id` | path | waitingroom_waiting_room_id | Yes |  |
| `zone_id` | path | waitingroom_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List Waiting Room Rules response |
| 4XX | List Waiting Room Rules response failure |

**Success Response Schema:**

[waitingroom_rules_response_collection](../schemas/waitingroom/waitingroom-rules-response-collection.md)

## Security

- **api_token**
- **api_email**
- **api_key**

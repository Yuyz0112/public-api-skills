# PUT /zones/{zone_id}/waiting_rooms/{waiting_room_id}/rules

**Resource:** [Waiting Room](../resources/Waiting-Room.md)
**Replace Waiting Room Rules**
**Operation ID:** `waiting-room-replace-waiting-room-rules`

Only available for the Waiting Room Advanced subscription. Replaces all rules for a waiting room.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `waiting_room_id` | path | waitingroom_waiting_room_id | Yes |  |
| `zone_id` | path | waitingroom_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [waitingroom_update_rules](../schemas/waitingroom/waitingroom-update-rules.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Replace Waiting Room Rules response |
| 4XX | Replace Waiting Room Rules response failure |

**Success Response Schema:**

[waitingroom_rules_response_collection](../schemas/waitingroom/waitingroom-rules-response-collection.md)

## Security

- **api_token**
- **api_email**
- **api_key**

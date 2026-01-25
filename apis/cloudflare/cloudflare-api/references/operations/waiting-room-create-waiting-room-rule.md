# POST /zones/{zone_id}/waiting_rooms/{waiting_room_id}/rules

**Resource:** [Waiting Room](../resources/Waiting-Room.md)
**Create Waiting Room Rule**
**Operation ID:** `waiting-room-create-waiting-room-rule`

Only available for the Waiting Room Advanced subscription. Creates a rule for a waiting room.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `waiting_room_id` | path | waitingroom_waiting_room_id | Yes |  |
| `zone_id` | path | waitingroom_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [waitingroom_create_rule](../schemas/waitingroom/waitingroom-create-rule.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Create Waiting Room Rule response |
| 4XX | Create Waiting Room Rule response failure |

**Success Response Schema:**

[waitingroom_rules_response_collection](../schemas/waitingroom/waitingroom-rules-response-collection.md)

## Security

- **api_token**
- **api_email**
- **api_key**

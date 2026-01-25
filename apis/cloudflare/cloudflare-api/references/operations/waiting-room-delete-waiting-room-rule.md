# DELETE /zones/{zone_id}/waiting_rooms/{waiting_room_id}/rules/{rule_id}

**Resource:** [Waiting Room](../resources/Waiting-Room.md)
**Delete Waiting Room Rule**
**Operation ID:** `waiting-room-delete-waiting-room-rule`

Deletes a rule for a waiting room.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `rule_id` | path | waitingroom_rule_id | Yes |  |
| `waiting_room_id` | path | waitingroom_waiting_room_id | Yes |  |
| `zone_id` | path | waitingroom_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Delete Waiting Room Rule response |
| 4XX | Delete Waiting Room Rule response failure |

**Success Response Schema:**

[waitingroom_rules_response_collection](../schemas/waitingroom/waitingroom-rules-response-collection.md)

## Security

- **api_token**
- **api_email**
- **api_key**

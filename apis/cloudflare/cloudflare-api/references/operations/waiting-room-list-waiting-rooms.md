# GET /zones/{zone_id}/waiting_rooms

**Resource:** [Waiting Room](../resources/Waiting-Room.md)
**List waiting rooms for zone**
**Operation ID:** `waiting-room-list-waiting-rooms`

Lists waiting rooms for zone.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | waitingroom_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List waiting rooms for zone response |
| 4XX | List waiting rooms for zone response failure |

**Success Response Schema:**

[waitingroom_response_collection](../schemas/waitingroom/waitingroom-response-collection.md)

## Security

- **api_token**
- **api_email**
- **api_key**

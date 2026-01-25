# POST /zones/{zone_id}/waiting_rooms

**Resource:** [Waiting Room](../resources/Waiting-Room.md)
**Create waiting room**
**Operation ID:** `waiting-room-create-waiting-room`

Creates a new waiting room.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | waitingroom_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [waitingroom_query_waitingroom](../schemas/waitingroom/waitingroom-query-waitingroom.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Create waiting room response |
| 4XX | Create waiting room response failure |

**Success Response Schema:**

[waitingroom_single_response](../schemas/waitingroom/waitingroom-single-response.md)

## Security

- **api_token**
- **api_email**
- **api_key**

# GET /accounts/{account_id}/waiting_rooms

**Resource:** [Waiting Room](../resources/Waiting-Room.md)
**List waiting rooms for account**
**Operation ID:** `waiting-room-list-waiting-rooms-account`

Lists waiting rooms for account.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | waitingroom_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List waiting rooms for account response |
| 4XX | List waiting rooms for account response failure |

**Success Response Schema:**

[waitingroom_response_collection](../schemas/waitingroom/waitingroom-response-collection.md)

## Security

- **api_token**
- **api_email**
- **api_key**

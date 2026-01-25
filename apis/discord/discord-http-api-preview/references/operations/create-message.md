# POST /channels/{channel_id}/messages

**Resource:** [channels](../resources/channels.md)
**Operation ID:** `create_message`

## Request Body

**Required:** Yes

**Content Types:** `application/json`, `application/x-www-form-urlencoded`, `multipart/form-data`

**Schema:** [MessageCreateRequest](../schemas/Message/MessageCreateRequest.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | 200 response for create_message |
| 429 | (reference) |
| 4XX | (reference) |

**Success Response Schema:**

[MessageResponse](../schemas/Message/MessageResponse.md)

## Security

- **BotToken**

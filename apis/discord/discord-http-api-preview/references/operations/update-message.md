# PATCH /channels/{channel_id}/messages/{message_id}

**Resource:** [channels](../resources/channels.md)
**Operation ID:** `update_message`

## Request Body

**Required:** Yes

**Content Types:** `application/json`, `application/x-www-form-urlencoded`, `multipart/form-data`

**Schema:** [MessageEditRequestPartial](../schemas/Message/MessageEditRequestPartial.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | 200 response for update_message |
| 429 | (reference) |
| 4XX | (reference) |

**Success Response Schema:**

[MessageResponse](../schemas/Message/MessageResponse.md)

## Security

- **BotToken**

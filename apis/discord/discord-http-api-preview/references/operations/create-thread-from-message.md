# POST /channels/{channel_id}/messages/{message_id}/threads

**Resource:** [channels](../resources/channels.md)
**Operation ID:** `create_thread_from_message`

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [CreateTextThreadWithMessageRequest](../schemas/Create/CreateTextThreadWithMessageRequest.md)

## Responses

| Status | Description |
|--------|-------------|
| 201 | 201 response for create_thread_from_message |
| 429 | (reference) |
| 4XX | (reference) |

**Success Response Schema:**

[ThreadResponse](../schemas/Thread/ThreadResponse.md)

## Security

- **BotToken**

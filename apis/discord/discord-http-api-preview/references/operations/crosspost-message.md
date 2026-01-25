# POST /channels/{channel_id}/messages/{message_id}/crosspost

**Resource:** [channels](../resources/channels.md)
**Operation ID:** `crosspost_message`

## Responses

| Status | Description |
|--------|-------------|
| 200 | 200 response for crosspost_message |
| 429 | (reference) |
| 4XX | (reference) |

**Success Response Schema:**

[MessageResponse](../schemas/Message/MessageResponse.md)

## Security

- **BotToken**

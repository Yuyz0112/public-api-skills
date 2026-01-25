# GET /channels/{channel_id}/messages/{message_id}

**Resource:** [channels](../resources/channels.md)
**Operation ID:** `get_message`

## Responses

| Status | Description |
|--------|-------------|
| 200 | 200 response for get_message |
| 429 | (reference) |
| 4XX | (reference) |

**Success Response Schema:**

[MessageResponse](../schemas/Message/MessageResponse.md)

## Security

- **BotToken**

# POST /channels/{channel_id}/webhooks

**Resource:** [channels](../resources/channels.md)
**Operation ID:** `create_webhook`

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | 200 response for create_webhook |
| 429 | (reference) |
| 4XX | (reference) |

**Success Response Schema:**

[GuildIncomingWebhookResponse](../schemas/Guild/GuildIncomingWebhookResponse.md)

## Security

- **BotToken**

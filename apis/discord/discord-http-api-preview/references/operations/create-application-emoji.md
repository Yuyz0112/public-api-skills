# POST /applications/{application_id}/emojis

**Resource:** [applications](../resources/applications.md)
**Operation ID:** `create_application_emoji`

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | 201 response for create_application_emoji |
| 429 | (reference) |
| 4XX | (reference) |

**Success Response Schema:**

[EmojiResponse](../schemas/Emoji/EmojiResponse.md)

## Security

- **BotToken**

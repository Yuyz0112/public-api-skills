# PATCH /applications/{application_id}/emojis/{emoji_id}

**Resource:** [applications](../resources/applications.md)
**Operation ID:** `update_application_emoji`

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | 200 response for update_application_emoji |
| 429 | (reference) |
| 4XX | (reference) |

**Success Response Schema:**

[EmojiResponse](../schemas/Emoji/EmojiResponse.md)

## Security

- **BotToken**

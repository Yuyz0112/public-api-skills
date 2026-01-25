# PATCH /guilds/{guild_id}/emojis/{emoji_id}

**Resource:** [guilds](../resources/guilds.md)
**Operation ID:** `update_guild_emoji`

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | 200 response for update_guild_emoji |
| 429 | (reference) |
| 4XX | (reference) |

**Success Response Schema:**

[EmojiResponse](../schemas/Emoji/EmojiResponse.md)

## Security

- **BotToken**

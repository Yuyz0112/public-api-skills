# POST /guilds/{guild_id}/emojis

**Resource:** [guilds](../resources/guilds.md)
**Operation ID:** `create_guild_emoji`

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | 201 response for create_guild_emoji |
| 429 | (reference) |
| 4XX | (reference) |

**Success Response Schema:**

[EmojiResponse](../schemas/Emoji/EmojiResponse.md)

## Security

- **BotToken**

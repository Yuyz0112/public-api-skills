# PATCH /guilds/{guild_id}/stickers/{sticker_id}

**Resource:** [guilds](../resources/guilds.md)
**Operation ID:** `update_guild_sticker`

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | 200 response for update_guild_sticker |
| 429 | (reference) |
| 4XX | (reference) |

**Success Response Schema:**

[GuildStickerResponse](../schemas/Guild/GuildStickerResponse.md)

## Security

- **BotToken**

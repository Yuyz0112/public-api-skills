# POST /guilds/{guild_id}/stickers

**Resource:** [guilds](../resources/guilds.md)
**Operation ID:** `create_guild_sticker`

## Request Body

**Required:** Yes

**Content Types:** `multipart/form-data`

## Responses

| Status | Description |
|--------|-------------|
| 201 | 201 response for create_guild_sticker |
| 429 | (reference) |
| 4XX | (reference) |

**Success Response Schema:**

[GuildStickerResponse](../schemas/Guild/GuildStickerResponse.md)

## Security

- **BotToken**

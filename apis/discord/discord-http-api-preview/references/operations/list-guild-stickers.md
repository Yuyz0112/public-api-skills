# GET /guilds/{guild_id}/stickers

**Resource:** [guilds](../resources/guilds.md)
**Operation ID:** `list_guild_stickers`

## Responses

| Status | Description |
|--------|-------------|
| 200 | 200 response for list_guild_stickers |
| 429 | (reference) |
| 4XX | (reference) |

**Success Response Schema:**

Array of [GuildStickerResponse](../schemas/Guild/GuildStickerResponse.md)

## Security

- **BotToken**

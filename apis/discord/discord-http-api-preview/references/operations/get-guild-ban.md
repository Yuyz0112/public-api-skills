# GET /guilds/{guild_id}/bans/{user_id}

**Resource:** [guilds](../resources/guilds.md)
**Operation ID:** `get_guild_ban`

## Responses

| Status | Description |
|--------|-------------|
| 200 | 200 response for get_guild_ban |
| 429 | (reference) |
| 4XX | (reference) |

**Success Response Schema:**

[GuildBanResponse](../schemas/Guild/GuildBanResponse.md)

## Security

- **BotToken**

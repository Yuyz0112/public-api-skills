# GET /guilds/{guild_id}/members/{user_id}

**Resource:** [guilds](../resources/guilds.md)
**Operation ID:** `get_guild_member`

## Responses

| Status | Description |
|--------|-------------|
| 200 | 200 response for get_guild_member |
| 429 | (reference) |
| 4XX | (reference) |

**Success Response Schema:**

[GuildMemberResponse](../schemas/Guild/GuildMemberResponse.md)

## Security

- **BotToken**

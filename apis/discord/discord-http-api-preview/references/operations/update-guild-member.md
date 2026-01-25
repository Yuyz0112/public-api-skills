# PATCH /guilds/{guild_id}/members/{user_id}

**Resource:** [guilds](../resources/guilds.md)
**Operation ID:** `update_guild_member`

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | 200 response for update_guild_member |
| 204 | 204 response for update_guild_member |
| 429 | (reference) |
| 4XX | (reference) |

**Success Response Schema:**

[GuildMemberResponse](../schemas/Guild/GuildMemberResponse.md)

## Security

- **BotToken**

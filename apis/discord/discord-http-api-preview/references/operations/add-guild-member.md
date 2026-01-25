# PUT /guilds/{guild_id}/members/{user_id}

**Resource:** [guilds](../resources/guilds.md)
**Operation ID:** `add_guild_member`

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [BotAddGuildMemberRequest](../schemas/Bot/BotAddGuildMemberRequest.md)

## Responses

| Status | Description |
|--------|-------------|
| 201 | 201 response for add_guild_member |
| 204 | 204 response for add_guild_member |
| 429 | (reference) |
| 4XX | (reference) |

**Success Response Schema:**

[GuildMemberResponse](../schemas/Guild/GuildMemberResponse.md)

## Security

- **BotToken**

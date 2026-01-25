# POST /guilds/{guild_id}/channels

**Resource:** [guilds](../resources/guilds.md)
**Operation ID:** `create_guild_channel`

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [CreateGuildChannelRequest](../schemas/Create/CreateGuildChannelRequest.md)

## Responses

| Status | Description |
|--------|-------------|
| 201 | 201 response for create_guild_channel |
| 429 | (reference) |
| 4XX | (reference) |

**Success Response Schema:**

[GuildChannelResponse](../schemas/Guild/GuildChannelResponse.md)

## Security

- **BotToken**

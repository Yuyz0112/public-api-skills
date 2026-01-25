# PATCH /guilds/{guild_id}

**Resource:** [guilds](../resources/guilds.md)
**Operation ID:** `update_guild`

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [GuildPatchRequestPartial](../schemas/Guild/GuildPatchRequestPartial.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | 200 response for update_guild |
| 429 | (reference) |
| 4XX | (reference) |

**Success Response Schema:**

[GuildResponse](../schemas/Guild/GuildResponse.md)

## Security

- **BotToken**

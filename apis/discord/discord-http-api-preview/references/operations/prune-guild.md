# POST /guilds/{guild_id}/prune

**Resource:** [guilds](../resources/guilds.md)
**Operation ID:** `prune_guild`

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [PruneGuildRequest](../schemas/Prune/PruneGuildRequest.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | 200 response for prune_guild |
| 429 | (reference) |
| 4XX | (reference) |

**Success Response Schema:**

[GuildPruneResponse](../schemas/Guild/GuildPruneResponse.md)

## Security

- **BotToken**

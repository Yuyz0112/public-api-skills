# GET /guilds/{guild_id}/roles

**Resource:** [guilds](../resources/guilds.md)
**Operation ID:** `list_guild_roles`

## Responses

| Status | Description |
|--------|-------------|
| 200 | 200 response for list_guild_roles |
| 429 | (reference) |
| 4XX | (reference) |

**Success Response Schema:**

Array of [GuildRoleResponse](../schemas/Guild/GuildRoleResponse.md)

## Security

- **BotToken**

# POST /guilds/{guild_id}/roles

**Resource:** [guilds](../resources/guilds.md)
**Operation ID:** `create_guild_role`

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [CreateRoleRequest](../schemas/Create/CreateRoleRequest.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | 200 response for create_guild_role |
| 429 | (reference) |
| 4XX | (reference) |

**Success Response Schema:**

[GuildRoleResponse](../schemas/Guild/GuildRoleResponse.md)

## Security

- **BotToken**

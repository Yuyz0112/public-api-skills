# PATCH /guilds/{guild_id}/roles/{role_id}

**Resource:** [guilds](../resources/guilds.md)
**Operation ID:** `update_guild_role`

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [UpdateRoleRequestPartial](../schemas/Update/UpdateRoleRequestPartial.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | 200 response for update_guild_role |
| 429 | (reference) |
| 4XX | (reference) |

**Success Response Schema:**

[GuildRoleResponse](../schemas/Guild/GuildRoleResponse.md)

## Security

- **BotToken**

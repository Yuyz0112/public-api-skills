# PATCH /guilds/{guild_id}/roles

**Resource:** [guilds](../resources/guilds.md)
**Operation ID:** `bulk_update_guild_roles`

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** Array of [UpdateRolePositionsRequest](../schemas/Update/UpdateRolePositionsRequest.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | 200 response for bulk_update_guild_roles |
| 429 | (reference) |
| 4XX | (reference) |

**Success Response Schema:**

Array of [GuildRoleResponse](../schemas/Guild/GuildRoleResponse.md)

## Security

- **BotToken**

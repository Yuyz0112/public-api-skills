# PATCH /guilds/{guild_id}/templates/{code}

**Resource:** [guilds](../resources/guilds.md)
**Operation ID:** `update_guild_template`

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | 200 response for update_guild_template |
| 429 | (reference) |
| 4XX | (reference) |

**Success Response Schema:**

[GuildTemplateResponse](../schemas/Guild/GuildTemplateResponse.md)

## Security

- **BotToken**

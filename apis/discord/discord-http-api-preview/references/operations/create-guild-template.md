# POST /guilds/{guild_id}/templates

**Resource:** [guilds](../resources/guilds.md)
**Operation ID:** `create_guild_template`

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | 200 response for create_guild_template |
| 429 | (reference) |
| 4XX | (reference) |

**Success Response Schema:**

[GuildTemplateResponse](../schemas/Guild/GuildTemplateResponse.md)

## Security

- **BotToken**

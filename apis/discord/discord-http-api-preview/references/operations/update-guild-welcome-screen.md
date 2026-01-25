# PATCH /guilds/{guild_id}/welcome-screen

**Resource:** [guilds](../resources/guilds.md)
**Operation ID:** `update_guild_welcome_screen`

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [WelcomeScreenPatchRequestPartial](../schemas/Welcome/WelcomeScreenPatchRequestPartial.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | 200 response for update_guild_welcome_screen |
| 429 | (reference) |
| 4XX | (reference) |

**Success Response Schema:**

[GuildWelcomeScreenResponse](../schemas/Guild/GuildWelcomeScreenResponse.md)

## Security

- **BotToken**

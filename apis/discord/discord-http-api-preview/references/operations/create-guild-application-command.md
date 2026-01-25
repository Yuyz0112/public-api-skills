# POST /applications/{application_id}/guilds/{guild_id}/commands

**Resource:** [applications](../resources/applications.md)
**Operation ID:** `create_guild_application_command`

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [ApplicationCommandCreateRequest](../schemas/Application/ApplicationCommandCreateRequest.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | 200 response for create_guild_application_command |
| 201 | 201 response for create_guild_application_command |
| 429 | (reference) |
| 4XX | (reference) |

**Success Response Schema:**

[ApplicationCommandResponse](../schemas/Application/ApplicationCommandResponse.md)

## Security

- **BotToken**
- **OAuth2**: applications.commands.update

# PATCH /applications/{application_id}/guilds/{guild_id}/commands/{command_id}

**Resource:** [applications](../resources/applications.md)
**Operation ID:** `update_guild_application_command`

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [ApplicationCommandPatchRequestPartial](../schemas/Application/ApplicationCommandPatchRequestPartial.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | 200 response for update_guild_application_command |
| 429 | (reference) |
| 4XX | (reference) |

**Success Response Schema:**

[ApplicationCommandResponse](../schemas/Application/ApplicationCommandResponse.md)

## Security

- **BotToken**
- **OAuth2**: applications.commands.update

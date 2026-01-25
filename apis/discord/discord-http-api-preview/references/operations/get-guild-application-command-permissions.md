# GET /applications/{application_id}/guilds/{guild_id}/commands/{command_id}/permissions

**Resource:** [applications](../resources/applications.md)
**Operation ID:** `get_guild_application_command_permissions`

## Responses

| Status | Description |
|--------|-------------|
| 200 | 200 response for get_guild_application_command_permissions |
| 429 | (reference) |
| 4XX | (reference) |

**Success Response Schema:**

[CommandPermissionsResponse](../schemas/Command/CommandPermissionsResponse.md)

## Security

- **BotToken**
- **OAuth2**: applications.commands.permissions.update

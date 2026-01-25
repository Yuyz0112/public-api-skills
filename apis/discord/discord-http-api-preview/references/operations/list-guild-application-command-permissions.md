# GET /applications/{application_id}/guilds/{guild_id}/commands/permissions

**Resource:** [applications](../resources/applications.md)
**Operation ID:** `list_guild_application_command_permissions`

## Responses

| Status | Description |
|--------|-------------|
| 200 | 200 response for list_guild_application_command_permissions |
| 429 | (reference) |
| 4XX | (reference) |

**Success Response Schema:**

Array of [CommandPermissionsResponse](../schemas/Command/CommandPermissionsResponse.md)

## Security

- **BotToken**
- **OAuth2**: applications.commands.permissions.update

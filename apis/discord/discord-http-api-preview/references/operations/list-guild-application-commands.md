# GET /applications/{application_id}/guilds/{guild_id}/commands

**Resource:** [applications](../resources/applications.md)
**Operation ID:** `list_guild_application_commands`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `with_localizations` | query | boolean | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | 200 response for list_guild_application_commands |
| 429 | (reference) |
| 4XX | (reference) |

## Security

- **BotToken**
- **OAuth2**: applications.commands.update

# GET /applications/{application_id}/commands/{command_id}

**Resource:** [applications](../resources/applications.md)
**Operation ID:** `get_application_command`

## Responses

| Status | Description |
|--------|-------------|
| 200 | 200 response for get_application_command |
| 429 | (reference) |
| 4XX | (reference) |

**Success Response Schema:**

[ApplicationCommandResponse](../schemas/Application/ApplicationCommandResponse.md)

## Security

- **BotToken**
- **OAuth2**: applications.commands.update

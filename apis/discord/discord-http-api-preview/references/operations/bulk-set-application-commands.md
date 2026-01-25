# PUT /applications/{application_id}/commands

**Resource:** [applications](../resources/applications.md)
**Operation ID:** `bulk_set_application_commands`

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | 200 response for bulk_set_application_commands |
| 429 | (reference) |
| 4XX | (reference) |

## Security

- **BotToken**
- **OAuth2**: applications.commands.update

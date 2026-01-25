# PATCH /guilds/{guild_id}/widget

**Resource:** [guilds](../resources/guilds.md)
**Operation ID:** `update_guild_widget_settings`

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | 200 response for update_guild_widget_settings |
| 429 | (reference) |
| 4XX | (reference) |

**Success Response Schema:**

[WidgetSettingsResponse](../schemas/Widget/WidgetSettingsResponse.md)

## Security

- **BotToken**

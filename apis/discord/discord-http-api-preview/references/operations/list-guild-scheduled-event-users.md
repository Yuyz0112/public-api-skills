# GET /guilds/{guild_id}/scheduled-events/{guild_scheduled_event_id}/users

**Resource:** [guilds](../resources/guilds.md)
**Operation ID:** `list_guild_scheduled_event_users`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `with_member` | query | boolean | No |  |
| `limit` | query | integer | No |  |
| `before` | query | SnowflakeType | No |  |
| `after` | query | SnowflakeType | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | 200 response for list_guild_scheduled_event_users |
| 429 | (reference) |
| 4XX | (reference) |

## Security

- **BotToken**

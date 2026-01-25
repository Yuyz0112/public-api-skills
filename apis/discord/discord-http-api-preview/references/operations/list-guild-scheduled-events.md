# GET /guilds/{guild_id}/scheduled-events

**Resource:** [guilds](../resources/guilds.md)
**Operation ID:** `list_guild_scheduled_events`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `with_user_count` | query | boolean | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | 200 response for list_guild_scheduled_events |
| 429 | (reference) |
| 4XX | (reference) |

## Security

- **BotToken**

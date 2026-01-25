# GET /guilds/{guild_id}/scheduled-events/{guild_scheduled_event_id}

**Resource:** [guilds](../resources/guilds.md)
**Operation ID:** `get_guild_scheduled_event`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `with_user_count` | query | boolean | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | 200 response for get_guild_scheduled_event |
| 429 | (reference) |
| 4XX | (reference) |

## Security

- **BotToken**

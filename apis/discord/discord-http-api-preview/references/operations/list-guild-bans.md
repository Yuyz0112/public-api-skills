# GET /guilds/{guild_id}/bans

**Resource:** [guilds](../resources/guilds.md)
**Operation ID:** `list_guild_bans`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `limit` | query | integer | No |  |
| `before` | query | SnowflakeType | No |  |
| `after` | query | SnowflakeType | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | 200 response for list_guild_bans |
| 429 | (reference) |
| 4XX | (reference) |

## Security

- **BotToken**

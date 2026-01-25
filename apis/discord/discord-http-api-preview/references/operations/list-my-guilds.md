# GET /users/@me/guilds

**Resource:** [users](../resources/users.md)
**Operation ID:** `list_my_guilds`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `before` | query | SnowflakeType | No |  |
| `after` | query | SnowflakeType | No |  |
| `limit` | query | integer | No |  |
| `with_counts` | query | boolean | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | 200 response for list_my_guilds |
| 429 | (reference) |
| 4XX | (reference) |

## Security

- **BotToken**
- **OAuth2**: guilds

# GET /guilds/{guild_id}

**Resource:** [guilds](../resources/guilds.md)
**Operation ID:** `get_guild`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `with_counts` | query | boolean | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | 200 response for get_guild |
| 429 | (reference) |
| 4XX | (reference) |

**Success Response Schema:**

[GuildWithCountsResponse](../schemas/Guild/GuildWithCountsResponse.md)

## Security

- **BotToken**

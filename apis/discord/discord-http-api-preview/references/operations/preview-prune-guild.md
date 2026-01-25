# GET /guilds/{guild_id}/prune

**Resource:** [guilds](../resources/guilds.md)
**Operation ID:** `preview_prune_guild`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `days` | query | integer | No |  |
| `include_roles` | query | any | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | 200 response for preview_prune_guild |
| 429 | (reference) |
| 4XX | (reference) |

**Success Response Schema:**

[GuildPruneResponse](../schemas/Guild/GuildPruneResponse.md)

## Security

- **BotToken**

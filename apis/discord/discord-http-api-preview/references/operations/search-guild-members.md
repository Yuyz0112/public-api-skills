# GET /guilds/{guild_id}/members/search

**Resource:** [guilds](../resources/guilds.md)
**Operation ID:** `search_guild_members`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `limit` | query | integer | No |  |
| `query` | query | string | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | 200 response for search_guild_members |
| 429 | (reference) |
| 4XX | (reference) |

**Success Response Schema:**

Array of [GuildMemberResponse](../schemas/Guild/GuildMemberResponse.md)

## Security

- **BotToken**

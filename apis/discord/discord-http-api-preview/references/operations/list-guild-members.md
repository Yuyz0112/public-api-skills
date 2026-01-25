# GET /guilds/{guild_id}/members

**Resource:** [guilds](../resources/guilds.md)
**Operation ID:** `list_guild_members`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `limit` | query | integer | No |  |
| `after` | query | integer | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | 200 response for list_guild_members |
| 429 | (reference) |
| 4XX | (reference) |

**Success Response Schema:**

Array of [GuildMemberResponse](../schemas/Guild/GuildMemberResponse.md)

## Security

- **BotToken**

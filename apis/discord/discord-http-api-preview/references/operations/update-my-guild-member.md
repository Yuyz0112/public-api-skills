# PATCH /guilds/{guild_id}/members/@me

**Resource:** [guilds](../resources/guilds.md)
**Operation ID:** `update_my_guild_member`

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | 200 response for update_my_guild_member |
| 429 | (reference) |
| 4XX | (reference) |

**Success Response Schema:**

[PrivateGuildMemberResponse](../schemas/Private/PrivateGuildMemberResponse.md)

## Security

- **BotToken**

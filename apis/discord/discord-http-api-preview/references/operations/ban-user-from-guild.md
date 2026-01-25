# PUT /guilds/{guild_id}/bans/{user_id}

**Resource:** [guilds](../resources/guilds.md)
**Operation ID:** `ban_user_from_guild`

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [BanUserFromGuildRequest](../schemas/Ban/BanUserFromGuildRequest.md)

## Responses

| Status | Description |
|--------|-------------|
| 204 | 204 response for ban_user_from_guild |
| 429 | (reference) |
| 4XX | (reference) |

## Security

- **BotToken**

# GET /users/@me/guilds/{guild_id}/member

**Resource:** [users](../resources/users.md)
**Operation ID:** `get_my_guild_member`

## Responses

| Status | Description |
|--------|-------------|
| 200 | 200 response for get_my_guild_member |
| 429 | (reference) |
| 4XX | (reference) |

**Success Response Schema:**

[PrivateGuildMemberResponse](../schemas/Private/PrivateGuildMemberResponse.md)

## Security

- **OAuth2**: guilds.members.read

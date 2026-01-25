# POST /lobbies/{lobby_id}/members/@me/invites

**Resource:** [lobbies](../resources/lobbies.md)
**Operation ID:** `create_linked_lobby_guild_invite_for_self`

## Responses

| Status | Description |
|--------|-------------|
| 200 | 200 response for create_linked_lobby_guild_invite_for_self |
| 429 | (reference) |
| 4XX | (reference) |

**Success Response Schema:**

[LobbyGuildInviteResponse](../schemas/Lobby/LobbyGuildInviteResponse.md)

## Security

- **BotToken**
- **OAuth2**

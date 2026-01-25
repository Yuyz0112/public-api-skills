# POST /lobbies/{lobby_id}/members/{user_id}/invites

**Resource:** [lobbies](../resources/lobbies.md)
**Operation ID:** `create_linked_lobby_guild_invite_for_user`

## Responses

| Status | Description |
|--------|-------------|
| 200 | 200 response for create_linked_lobby_guild_invite_for_user |
| 429 | (reference) |
| 4XX | (reference) |

**Success Response Schema:**

[LobbyGuildInviteResponse](../schemas/Lobby/LobbyGuildInviteResponse.md)

## Security

- **BotToken**

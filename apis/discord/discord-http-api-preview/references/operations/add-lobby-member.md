# PUT /lobbies/{lobby_id}/members/{user_id}

**Resource:** [lobbies](../resources/lobbies.md)
**Operation ID:** `add_lobby_member`

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | 200 response for add_lobby_member |
| 429 | (reference) |
| 4XX | (reference) |

**Success Response Schema:**

[LobbyMemberResponse](../schemas/Lobby/LobbyMemberResponse.md)

## Security

- **BotToken**

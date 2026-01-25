# PATCH /lobbies/{lobby_id}

**Resource:** [lobbies](../resources/lobbies.md)
**Operation ID:** `edit_lobby`

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | 200 response for edit_lobby |
| 429 | (reference) |
| 4XX | (reference) |

**Success Response Schema:**

[LobbyResponse](../schemas/Lobby/LobbyResponse.md)

## Security

- **BotToken**

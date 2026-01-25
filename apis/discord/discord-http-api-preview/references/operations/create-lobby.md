# POST /lobbies

**Resource:** [lobbies](../resources/lobbies.md)
**Operation ID:** `create_lobby`

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | 201 response for create_lobby |
| 429 | (reference) |
| 4XX | (reference) |

**Success Response Schema:**

[LobbyResponse](../schemas/Lobby/LobbyResponse.md)

## Security

- **BotToken**

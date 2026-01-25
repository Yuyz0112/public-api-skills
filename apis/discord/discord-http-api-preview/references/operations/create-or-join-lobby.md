# PUT /lobbies

**Resource:** [lobbies](../resources/lobbies.md)
**Operation ID:** `create_or_join_lobby`

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | 200 response for create_or_join_lobby |
| 429 | (reference) |
| 4XX | (reference) |

**Success Response Schema:**

[LobbyResponse](../schemas/Lobby/LobbyResponse.md)

## Security

- **BotToken**
- **OAuth2**

# POST /lobbies/{lobby_id}/messages

**Resource:** [lobbies](../resources/lobbies.md)
**Operation ID:** `create_lobby_message`

## Request Body

**Required:** Yes

**Content Types:** `application/json`, `application/x-www-form-urlencoded`, `multipart/form-data`

**Schema:** [SDKMessageRequest](../schemas/SDKMessageRequest/SDKMessageRequest.md)

## Responses

| Status | Description |
|--------|-------------|
| 201 | 201 response for create_lobby_message |
| 429 | (reference) |
| 4XX | (reference) |

**Success Response Schema:**

[LobbyMessageResponse](../schemas/Lobby/LobbyMessageResponse.md)

## Security

- **BotToken**
- **OAuth2**

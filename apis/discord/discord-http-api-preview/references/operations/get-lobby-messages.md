# GET /lobbies/{lobby_id}/messages

**Resource:** [lobbies](../resources/lobbies.md)
**Operation ID:** `get_lobby_messages`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `limit` | query | integer | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | 200 response for get_lobby_messages |
| 429 | (reference) |
| 4XX | (reference) |

## Security

- **BotToken**
- **OAuth2**

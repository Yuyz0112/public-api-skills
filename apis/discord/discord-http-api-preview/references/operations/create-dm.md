# POST /users/@me/channels

**Resource:** [users](../resources/users.md)
**Operation ID:** `create_dm`

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [CreatePrivateChannelRequest](../schemas/Create/CreatePrivateChannelRequest.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | 200 response for create_dm |
| 429 | (reference) |
| 4XX | (reference) |

## Security

- **BotToken**

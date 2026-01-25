# GET /users/@me

**Resource:** [users](../resources/users.md)
**Operation ID:** `get_my_user`

## Responses

| Status | Description |
|--------|-------------|
| 200 | 200 response for get_my_user |
| 429 | (reference) |
| 4XX | (reference) |

**Success Response Schema:**

[UserPIIResponse](../schemas/User/UserPIIResponse.md)

## Security

- **BotToken**
- **OAuth2**: identify

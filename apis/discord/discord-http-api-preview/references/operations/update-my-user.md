# PATCH /users/@me

**Resource:** [users](../resources/users.md)
**Operation ID:** `update_my_user`

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [BotAccountPatchRequest](../schemas/Bot/BotAccountPatchRequest.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | 200 response for update_my_user |
| 429 | (reference) |
| 4XX | (reference) |

**Success Response Schema:**

[UserPIIResponse](../schemas/User/UserPIIResponse.md)

## Security

- **BotToken**

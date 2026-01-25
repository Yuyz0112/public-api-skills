# GET /2/users/me

**Resource:** [Users](../resources/Users.md)
**Get my User**
**Operation ID:** `getUsersMe`

Retrieves details of the authenticated user.

## Responses

| Status | Description |
|--------|-------------|
| 200 | The request has succeeded. |
| default | The request has failed. |

**Success Response Schema:**

[Get2UsersMeResponse](../schemas/Get/Get2UsersMeResponse.md)

## Security

- **OAuth2UserToken**: tweet.read, users.read
- **UserToken**

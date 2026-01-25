# GET /2/users/by/username/{username}

**Resource:** [Users](../resources/Users.md)
**Get User by username**
**Operation ID:** `getUsersByUsername`

Retrieves details of a specific User by their username.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `username` | path | string | Yes | A username. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | The request has succeeded. |
| default | The request has failed. |

**Success Response Schema:**

[Get2UsersByUsernameUsernameResponse](../schemas/Get/Get2UsersByUsernameUsernameResponse.md)

## Security

- **BearerToken**
- **OAuth2UserToken**: tweet.read, users.read
- **UserToken**

# GET /2/users/{id}

**Resource:** [Users](../resources/Users.md)
**Get User by ID**
**Operation ID:** `getUsersById`

Retrieves details of a specific User by their ID.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | UserId | Yes | The ID of the User to lookup. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | The request has succeeded. |
| default | The request has failed. |

**Success Response Schema:**

[Get2UsersIdResponse](../schemas/Get/Get2UsersIdResponse.md)

## Security

- **BearerToken**
- **OAuth2UserToken**: tweet.read, users.read
- **UserToken**

# POST /2/users/{id}/muting

**Resource:** [Users](../resources/Users.md)
**Mute User**
**Operation ID:** `muteUser`

Causes the authenticated user to mute a specific User by their ID.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | UserIdMatchesAuthenticatedUser | Yes | The ID of the authenticated source User that is requesting to mute the target User. |

## Request Body

**Content Types:** `application/json`

**Schema:** [MuteUserRequest](../schemas/Mute/MuteUserRequest.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | The request has succeeded. |
| default | The request has failed. |

**Success Response Schema:**

[MuteUserMutationResponse](../schemas/Mute/MuteUserMutationResponse.md)

## Security

- **OAuth2UserToken**: mute.write, tweet.read, users.read
- **UserToken**

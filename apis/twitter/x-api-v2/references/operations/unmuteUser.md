# DELETE /2/users/{source_user_id}/muting/{target_user_id}

**Resource:** [Users](../resources/Users.md)
**Unmute User**
**Operation ID:** `unmuteUser`

Causes the authenticated user to unmute a specific user by their ID.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `source_user_id` | path | UserIdMatchesAuthenticatedUser | Yes | The ID of the authenticated source User that is requesting to unmute the target User. |
| `target_user_id` | path | UserId | Yes | The ID of the User that the source User is requesting to unmute. |

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

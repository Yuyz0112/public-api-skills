# DELETE /2/users/{source_user_id}/following/{target_user_id}

**Resource:** [Users](../resources/Users.md)
**Unfollow User**
**Operation ID:** `unfollowUser`

Causes the authenticated user to unfollow a specific user by their ID.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `source_user_id` | path | UserIdMatchesAuthenticatedUser | Yes | The ID of the authenticated source User that is requesting to unfollow the target User. |
| `target_user_id` | path | UserId | Yes | The ID of the User that the source User is requesting to unfollow. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | The request has succeeded. |
| default | The request has failed. |

**Success Response Schema:**

[UsersFollowingDeleteResponse](../schemas/Users/UsersFollowingDeleteResponse.md)

## Security

- **OAuth2UserToken**: follows.write, tweet.read, users.read
- **UserToken**

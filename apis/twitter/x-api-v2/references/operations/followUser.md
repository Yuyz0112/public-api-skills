# POST /2/users/{id}/following

**Resource:** [Users](../resources/Users.md)
**Follow User**
**Operation ID:** `followUser`

Causes the authenticated user to follow a specific user by their ID.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | UserIdMatchesAuthenticatedUser | Yes | The ID of the authenticated source User that is requesting to follow the target User. |

## Request Body

**Content Types:** `application/json`

**Schema:** [UsersFollowingCreateRequest](../schemas/Users/UsersFollowingCreateRequest.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | The request has succeeded. |
| default | The request has failed. |

**Success Response Schema:**

[UsersFollowingCreateResponse](../schemas/Users/UsersFollowingCreateResponse.md)

## Security

- **OAuth2UserToken**: follows.write, tweet.read, users.read
- **UserToken**

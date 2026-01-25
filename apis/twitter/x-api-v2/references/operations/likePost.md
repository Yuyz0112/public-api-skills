# POST /2/users/{id}/likes

**Resource:** [Tweets](../resources/Tweets.md)
**Like Post**
**Operation ID:** `likePost`

Causes the authenticated user to Like a specific Post by its ID.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | UserIdMatchesAuthenticatedUser | Yes | The ID of the authenticated source User that is requesting to like the Post. |

## Request Body

**Content Types:** `application/json`

**Schema:** [UsersLikesCreateRequest](../schemas/Users/UsersLikesCreateRequest.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | The request has succeeded. |
| default | The request has failed. |

**Success Response Schema:**

[UsersLikesCreateResponse](../schemas/Users/UsersLikesCreateResponse.md)

## Security

- **OAuth2UserToken**: like.write, tweet.read, users.read
- **UserToken**

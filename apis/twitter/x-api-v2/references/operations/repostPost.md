# POST /2/users/{id}/retweets

**Resource:** [Tweets](../resources/Tweets.md)
**Repost Post**
**Operation ID:** `repostPost`

Causes the authenticated user to repost a specific Post by its ID.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | UserIdMatchesAuthenticatedUser | Yes | The ID of the authenticated source User that is requesting to repost the Post. |

## Request Body

**Content Types:** `application/json`

**Schema:** [UsersRetweetsCreateRequest](../schemas/Users/UsersRetweetsCreateRequest.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | The request has succeeded. |
| default | The request has failed. |

**Success Response Schema:**

[UsersRetweetsCreateResponse](../schemas/Users/UsersRetweetsCreateResponse.md)

## Security

- **OAuth2UserToken**: tweet.read, tweet.write, users.read
- **UserToken**

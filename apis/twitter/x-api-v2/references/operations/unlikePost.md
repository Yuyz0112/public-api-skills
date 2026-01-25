# DELETE /2/users/{id}/likes/{tweet_id}

**Resource:** [Tweets](../resources/Tweets.md)
**Unlike Post**
**Operation ID:** `unlikePost`

Causes the authenticated user to Unlike a specific Post by its ID.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | UserIdMatchesAuthenticatedUser | Yes | The ID of the authenticated source User that is requesting to unlike the Post. |
| `tweet_id` | path | TweetId | Yes | The ID of the Post that the User is requesting to unlike. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | The request has succeeded. |
| default | The request has failed. |

**Success Response Schema:**

[UsersLikesDeleteResponse](../schemas/Users/UsersLikesDeleteResponse.md)

## Security

- **OAuth2UserToken**: like.write, tweet.read, users.read
- **UserToken**

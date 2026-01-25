# DELETE /2/users/{id}/retweets/{source_tweet_id}

**Resource:** [Tweets](../resources/Tweets.md)
**Unrepost Post**
**Operation ID:** `unrepostPost`

Causes the authenticated user to unrepost a specific Post by its ID.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | UserIdMatchesAuthenticatedUser | Yes | The ID of the authenticated source User that is requesting to repost the Post. |
| `source_tweet_id` | path | TweetId | Yes | The ID of the Post that the User is requesting to unretweet. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | The request has succeeded. |
| default | The request has failed. |

**Success Response Schema:**

[UsersRetweetsDeleteResponse](../schemas/Users/UsersRetweetsDeleteResponse.md)

## Security

- **OAuth2UserToken**: tweet.read, tweet.write, users.read
- **UserToken**

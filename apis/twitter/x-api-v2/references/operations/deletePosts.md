# DELETE /2/tweets/{id}

**Resource:** [Tweets](../resources/Tweets.md)
**Delete Post**
**Operation ID:** `deletePosts`

Deletes a specific Post by its ID, if owned by the authenticated user.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | TweetId | Yes | The ID of the Post to be deleted. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | The request has succeeded. |
| default | The request has failed. |

**Success Response Schema:**

[TweetDeleteResponse](../schemas/Tweet/TweetDeleteResponse.md)

## Security

- **OAuth2UserToken**: tweet.read, tweet.write, users.read
- **UserToken**

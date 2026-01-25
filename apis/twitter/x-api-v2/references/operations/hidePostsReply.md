# PUT /2/tweets/{tweet_id}/hidden

**Resource:** [Tweets](../resources/Tweets.md)
**Hide reply**
**Operation ID:** `hidePostsReply`

Hides or unhides a reply to a conversation owned by the authenticated user.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `tweet_id` | path | TweetId | Yes | The ID of the reply that you want to hide or unhide. |

## Request Body

**Content Types:** `application/json`

**Schema:** [TweetHideRequest](../schemas/Tweet/TweetHideRequest.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | The request has succeeded. |
| default | The request has failed. |

**Success Response Schema:**

[TweetHideResponse](../schemas/Tweet/TweetHideResponse.md)

## Security

- **OAuth2UserToken**: tweet.moderate.write, tweet.read, users.read
- **UserToken**

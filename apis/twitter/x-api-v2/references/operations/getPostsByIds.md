# GET /2/tweets

**Resource:** [Tweets](../resources/Tweets.md)
**Get Posts by IDs**
**Operation ID:** `getPostsByIds`

Retrieves details of multiple Posts by their IDs.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `ids` | query | TweetId[] | Yes | A comma separated list of Post IDs. Up to 100 are allowed in a single request. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | The request has succeeded. |
| default | The request has failed. |

**Success Response Schema:**

[Get2TweetsResponse](../schemas/Get/Get2TweetsResponse.md)

## Security

- **BearerToken**
- **OAuth2UserToken**: tweet.read, users.read
- **UserToken**

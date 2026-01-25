# GET /2/tweets/{id}

**Resource:** [Tweets](../resources/Tweets.md)
**Get Post by ID**
**Operation ID:** `getPostsById`

Retrieves details of a specific Post by its ID.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | TweetId | Yes | A single Post ID. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | The request has succeeded. |
| default | The request has failed. |

**Success Response Schema:**

[Get2TweetsIdResponse](../schemas/Get/Get2TweetsIdResponse.md)

## Security

- **BearerToken**
- **OAuth2UserToken**: tweet.read, users.read
- **UserToken**

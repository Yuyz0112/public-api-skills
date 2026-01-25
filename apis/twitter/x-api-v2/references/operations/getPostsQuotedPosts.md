# GET /2/tweets/{id}/quote_tweets

**Resource:** [Tweets](../resources/Tweets.md)
**Get Quoted Posts**
**Operation ID:** `getPostsQuotedPosts`

Retrieves a list of Posts that quote a specific Post by its ID.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | TweetId | Yes | A single Post ID. |
| `max_results` | query | integer (int32) | No | The maximum number of results to be returned. |
| `pagination_token` | query | PaginationToken36 | No | This parameter is used to get a specified 'page' of results. |
| `exclude` | query | string[] | No | The set of entities to exclude (e.g. 'replies' or 'retweets'). |

## Responses

| Status | Description |
|--------|-------------|
| 200 | The request has succeeded. |
| default | The request has failed. |

**Success Response Schema:**

[Get2TweetsIdQuoteTweetsResponse](../schemas/Get/Get2TweetsIdQuoteTweetsResponse.md)

## Security

- **BearerToken**
- **OAuth2UserToken**: tweet.read, users.read
- **UserToken**

# GET /2/tweets/{id}/retweeted_by

**Resource:** [Tweets](../resources/Tweets.md)
**Get Reposted by**
**Operation ID:** `getPostsRepostedBy`

Retrieves a list of Users who reposted a specific Post by its ID.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | TweetId | Yes | A single Post ID. |
| `max_results` | query | integer (int32) | No | The maximum number of results. |
| `pagination_token` | query | PaginationToken36 | No | This parameter is used to get the next 'page' of results. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | The request has succeeded. |
| default | The request has failed. |

**Success Response Schema:**

[Get2TweetsIdRetweetedByResponse](../schemas/Get/Get2TweetsIdRetweetedByResponse.md)

## Security

- **BearerToken**
- **OAuth2UserToken**: tweet.read, users.read
- **UserToken**

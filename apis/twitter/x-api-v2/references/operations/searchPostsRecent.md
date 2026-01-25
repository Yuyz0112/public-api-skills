# GET /2/tweets/search/recent

**Resource:** [Tweets](../resources/Tweets.md)
**Search recent Posts**
**Operation ID:** `searchPostsRecent`

Retrieves Posts from the last 7 days matching a search query.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `query` | query | string | Yes | One query/rule/filter for matching Posts. Refer to https://t.co/rulelength to identify the max query length. |
| `start_time` | query | string (date-time) | No | YYYY-MM-DDTHH:mm:ssZ. The oldest UTC timestamp from which the Posts will be provided. Timestamp is in second granularity and is inclusive (i.e. 12:00:01 includes the first second of the minute). |
| `end_time` | query | string (date-time) | No | YYYY-MM-DDTHH:mm:ssZ. The newest, most recent UTC timestamp to which the Posts will be provided. Timestamp is in second granularity and is exclusive (i.e. 12:00:01 excludes the first second of the minute). |
| `since_id` | query | TweetId | No | Returns results with a Post ID greater than (that is, more recent than) the specified ID. |
| `until_id` | query | TweetId | No | Returns results with a Post ID less than (that is, older than) the specified ID. |
| `max_results` | query | integer (int32) | No | The maximum number of search results to be returned by a request. |
| `next_token` | query | PaginationToken36 | No | This parameter is used to get the next 'page' of results. The value used with the parameter is pulled directly from the response provided by the API, and should not be modified. |
| `pagination_token` | query | PaginationToken36 | No | This parameter is used to get the next 'page' of results. The value used with the parameter is pulled directly from the response provided by the API, and should not be modified. |
| `sort_order` | query | enum: recency, relevancy | No | This order in which to return results. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | The request has succeeded. |
| default | The request has failed. |

**Success Response Schema:**

[Get2TweetsSearchRecentResponse](../schemas/Get/Get2TweetsSearchRecentResponse.md)

## Security

- **BearerToken**
- **OAuth2UserToken**: tweet.read, users.read
- **UserToken**

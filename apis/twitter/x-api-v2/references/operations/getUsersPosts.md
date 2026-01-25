# GET /2/users/{id}/tweets

**Resource:** [Tweets](../resources/Tweets.md)
**Get Posts**
**Operation ID:** `getUsersPosts`

Retrieves a list of posts authored by a specific User by their ID.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | UserId | Yes | The ID of the User to lookup. |
| `since_id` | query | TweetId | No | The minimum Post ID to be included in the result set. This parameter takes precedence over start_time if both are specified. |
| `until_id` | query | TweetId | No | The maximum Post ID to be included in the result set. This parameter takes precedence over end_time if both are specified. |
| `max_results` | query | integer (int32) | No | The maximum number of results. |
| `pagination_token` | query | PaginationToken36 | No | This parameter is used to get the next 'page' of results. |
| `exclude` | query | string[] | No | The set of entities to exclude (e.g. 'replies' or 'retweets'). |
| `start_time` | query | string (date-time) | No | YYYY-MM-DDTHH:mm:ssZ. The earliest UTC timestamp from which the Posts will be provided. The since_id parameter takes precedence if it is also specified. |
| `end_time` | query | string (date-time) | No | YYYY-MM-DDTHH:mm:ssZ. The latest UTC timestamp to which the Posts will be provided. The until_id parameter takes precedence if it is also specified. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | The request has succeeded. |
| default | The request has failed. |

**Success Response Schema:**

[Get2UsersIdTweetsResponse](../schemas/Get/Get2UsersIdTweetsResponse.md)

## Security

- **BearerToken**
- **OAuth2UserToken**: tweet.read, users.read
- **UserToken**

# GET /2/users/{id}/liked_tweets

**Resource:** [Tweets](../resources/Tweets.md)
**Get liked Posts**
**Operation ID:** `getUsersLikedPosts`

Retrieves a list of Posts liked by a specific User by their ID.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | UserId | Yes | The ID of the User to lookup. |
| `max_results` | query | integer (int32) | No | The maximum number of results. |
| `pagination_token` | query | PaginationToken36 | No | This parameter is used to get the next 'page' of results. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | The request has succeeded. |
| default | The request has failed. |

**Success Response Schema:**

[Get2UsersIdLikedTweetsResponse](../schemas/Get/Get2UsersIdLikedTweetsResponse.md)

## Security

- **OAuth2UserToken**: like.read, tweet.read, users.read
- **UserToken**

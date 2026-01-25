# GET /2/users/search

**Resource:** [Users](../resources/Users.md)
**Search Users**
**Operation ID:** `searchUsers`

Retrieves a list of Users matching a search query.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `query` | query | UserSearchQueryVnext | Yes | TThe the query string by which to query for users. |
| `max_results` | query | integer (int32) | No | The maximum number of results. |
| `next_token` | query | PaginationToken36 | No | This parameter is used to get the next 'page' of results. The value used with the parameter is pulled directly from the response provided by the API, and should not be modified. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | The request has succeeded. |
| default | The request has failed. |

**Success Response Schema:**

[Get2UsersSearchResponse](../schemas/Get/Get2UsersSearchResponse.md)

## Security

- **OAuth2UserToken**: tweet.read, users.read
- **UserToken**

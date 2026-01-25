# GET /2/users/{id}/following

**Resource:** [Users](../resources/Users.md)
**Get following**
**Operation ID:** `getUsersFollowing`

Retrieves a list of Users followed by a specific User by their ID.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | UserId | Yes | The ID of the User to lookup. |
| `max_results` | query | integer (int32) | No | The maximum number of results. |
| `pagination_token` | query | PaginationToken32 | No | This parameter is used to get a specified 'page' of results. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | The request has succeeded. |
| default | The request has failed. |

**Success Response Schema:**

[Get2UsersIdFollowingResponse](../schemas/Get/Get2UsersIdFollowingResponse.md)

## Security

- **BearerToken**
- **OAuth2UserToken**: follows.read, tweet.read, users.read
- **UserToken**

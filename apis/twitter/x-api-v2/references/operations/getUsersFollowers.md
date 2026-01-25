# GET /2/users/{id}/followers

**Resource:** [Users](../resources/Users.md)
**Get followers**
**Operation ID:** `getUsersFollowers`

Retrieves a list of Users who follow a specific User by their ID.

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

[Get2UsersIdFollowersResponse](../schemas/Get/Get2UsersIdFollowersResponse.md)

## Security

- **BearerToken**
- **OAuth2UserToken**: follows.read, tweet.read, users.read
- **UserToken**

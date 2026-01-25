# GET /2/users/{id}/blocking

**Resource:** [Users](../resources/Users.md)
**Get blocking**
**Operation ID:** `getUsersBlocking`

Retrieves a list of Users blocked by the specified User ID.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | UserIdMatchesAuthenticatedUser | Yes | The ID of the authenticated source User for whom to return results. |
| `max_results` | query | integer (int32) | No | The maximum number of results. |
| `pagination_token` | query | PaginationToken32 | No | This parameter is used to get a specified 'page' of results. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | The request has succeeded. |
| default | The request has failed. |

**Success Response Schema:**

[Get2UsersIdBlockingResponse](../schemas/Get/Get2UsersIdBlockingResponse.md)

## Security

- **OAuth2UserToken**: block.read, tweet.read, users.read
- **UserToken**

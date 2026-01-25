# GET /2/users/{id}/muting

**Resource:** [Users](../resources/Users.md)
**Get muting**
**Operation ID:** `getUsersMuting`

Retrieves a list of Users muted by the authenticated user.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | UserIdMatchesAuthenticatedUser | Yes | The ID of the authenticated source User for whom to return results. |
| `max_results` | query | integer (int32) | No | The maximum number of results. |
| `pagination_token` | query | PaginationTokenLong | No | This parameter is used to get the next 'page' of results. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | The request has succeeded. |
| default | The request has failed. |

**Success Response Schema:**

[Get2UsersIdMutingResponse](../schemas/Get/Get2UsersIdMutingResponse.md)

## Security

- **OAuth2UserToken**: mute.read, tweet.read, users.read
- **UserToken**

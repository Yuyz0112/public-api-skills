# GET /2/users/reposts_of_me

**Resource:** [Users](../resources/Users.md)
**Get Reposts of me**
**Operation ID:** `getUsersRepostsOfMe`

Retrieves a list of Posts that repost content from the authenticated user.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `max_results` | query | integer (int32) | No | The maximum number of results. |
| `pagination_token` | query | PaginationToken36 | No | This parameter is used to get the next 'page' of results. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | The request has succeeded. |
| default | The request has failed. |

**Success Response Schema:**

[Get2UsersRepostsOfMeResponse](../schemas/Get/Get2UsersRepostsOfMeResponse.md)

## Security

- **OAuth2UserToken**: timeline.read, tweet.read
- **UserToken**

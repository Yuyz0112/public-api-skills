# GET /2/users/{id}/bookmarks

**Resource:** [Bookmarks](../resources/Bookmarks.md)
**Get Bookmarks**
**Operation ID:** `getUsersBookmarks`

Retrieves a list of Posts bookmarked by the authenticated user.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | UserIdMatchesAuthenticatedUser | Yes | The ID of the authenticated source User for whom to return results. |
| `max_results` | query | integer (int32) | No | The maximum number of results. |
| `pagination_token` | query | PaginationToken36 | No | This parameter is used to get the next 'page' of results. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | The request has succeeded. |
| default | The request has failed. |

**Success Response Schema:**

[Get2UsersIdBookmarksResponse](../schemas/Get/Get2UsersIdBookmarksResponse.md)

## Security

- **OAuth2UserToken**: bookmark.read, tweet.read, users.read

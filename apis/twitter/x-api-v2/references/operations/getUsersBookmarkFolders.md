# GET /2/users/{id}/bookmarks/folders

**Resource:** [Bookmarks](../resources/Bookmarks.md)
**Get Bookmark folders**
**Operation ID:** `getUsersBookmarkFolders`

Retrieves a list of Bookmark folders created by the authenticated user.

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

[BookmarkFoldersResponse](../schemas/Bookmark/BookmarkFoldersResponse.md)

## Security

- **OAuth2UserToken**: bookmark.read, users.read

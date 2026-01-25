# GET /2/users/{id}/bookmarks/folders/{folder_id}

**Resource:** [Bookmarks](../resources/Bookmarks.md)
**Get Bookmarks by folder ID**
**Operation ID:** `getUsersBookmarksByFolderId`

Retrieves Posts in a specific Bookmark folder by its ID for the authenticated user.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | UserIdMatchesAuthenticatedUser | Yes | The ID of the authenticated source User for whom to return results. |
| `folder_id` | path | BookmarkFolderId | Yes | The ID of the Bookmark Folder that the authenticated User is trying to fetch Posts for. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | The request has succeeded. |
| default | The request has failed. |

**Success Response Schema:**

[BookmarkFolderPostsResponse](../schemas/Bookmark/BookmarkFolderPostsResponse.md)

## Security

- **OAuth2UserToken**: bookmark.read, tweet.read, users.read

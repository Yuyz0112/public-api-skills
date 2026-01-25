# POST /2/users/{id}/bookmarks

**Resource:** [Bookmarks](../resources/Bookmarks.md)
**Create Bookmark**
**Operation ID:** `createUsersBookmark`

Adds a post to the authenticated user’s bookmarks.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | UserIdMatchesAuthenticatedUser | Yes | The ID of the authenticated source User for whom to add bookmarks. |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [BookmarkAddRequest](../schemas/Bookmark/BookmarkAddRequest.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | The request has succeeded. |
| default | The request has failed. |

**Success Response Schema:**

[BookmarkMutationResponse](../schemas/Bookmark/BookmarkMutationResponse.md)

## Security

- **OAuth2UserToken**: bookmark.write, tweet.read, users.read

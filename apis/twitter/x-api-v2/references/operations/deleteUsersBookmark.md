# DELETE /2/users/{id}/bookmarks/{tweet_id}

**Resource:** [Bookmarks](../resources/Bookmarks.md)
**Delete Bookmark**
**Operation ID:** `deleteUsersBookmark`

Removes a Post from the authenticated user’s Bookmarks by its ID.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | UserIdMatchesAuthenticatedUser | Yes | The ID of the authenticated source User whose bookmark is to be removed. |
| `tweet_id` | path | TweetId | Yes | The ID of the Post that the source User is removing from bookmarks. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | The request has succeeded. |
| default | The request has failed. |

**Success Response Schema:**

[BookmarkMutationResponse](../schemas/Bookmark/BookmarkMutationResponse.md)

## Security

- **OAuth2UserToken**: bookmark.write, tweet.read, users.read

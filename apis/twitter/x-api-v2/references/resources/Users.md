# Users

Endpoints related to retrieving, managing relationships of Users

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/2/lists/{id}/followers` | Get List followers | [View](../operations/getListsFollowers.md) |
| GET | `/2/lists/{id}/members` | Get List members | [View](../operations/getListsMembers.md) |
| GET | `/2/tweets/{id}/liking_users` | Get Liking Users | [View](../operations/getPostsLikingUsers.md) |
| GET | `/2/tweets/{id}/retweeted_by` | Get Reposted by | [View](../operations/getPostsRepostedBy.md) |
| GET | `/2/users` | Get Users by IDs | [View](../operations/getUsersByIds.md) |
| GET | `/2/users/by` | Get Users by usernames | [View](../operations/getUsersByUsernames.md) |
| GET | `/2/users/by/username/{username}` | Get User by username | [View](../operations/getUsersByUsername.md) |
| GET | `/2/users/me` | Get my User | [View](../operations/getUsersMe.md) |
| GET | `/2/users/reposts_of_me` | Get Reposts of me | [View](../operations/getUsersRepostsOfMe.md) |
| GET | `/2/users/search` | Search Users | [View](../operations/searchUsers.md) |
| GET | `/2/users/{id}` | Get User by ID | [View](../operations/getUsersById.md) |
| GET | `/2/users/{id}/blocking` | Get blocking | [View](../operations/getUsersBlocking.md) |
| GET | `/2/users/{id}/bookmarks` | Get Bookmarks | [View](../operations/getUsersBookmarks.md) |
| POST | `/2/users/{id}/bookmarks` | Create Bookmark | [View](../operations/createUsersBookmark.md) |
| GET | `/2/users/{id}/bookmarks/folders` | Get Bookmark folders | [View](../operations/getUsersBookmarkFolders.md) |
| GET | `/2/users/{id}/bookmarks/folders/{folder_id}` | Get Bookmarks by folder ID | [View](../operations/getUsersBookmarksByFolderId.md) |
| DELETE | `/2/users/{id}/bookmarks/{tweet_id}` | Delete Bookmark | [View](../operations/deleteUsersBookmark.md) |
| POST | `/2/users/{id}/dm/block` | Block DMs | [View](../operations/blockUsersDms.md) |
| POST | `/2/users/{id}/dm/unblock` | Unblock DMs | [View](../operations/unblockUsersDms.md) |
| GET | `/2/users/{id}/followed_lists` | Get followed Lists | [View](../operations/getUsersFollowedLists.md) |
| POST | `/2/users/{id}/followed_lists` | Follow List | [View](../operations/followList.md) |
| DELETE | `/2/users/{id}/followed_lists/{list_id}` | Unfollow List | [View](../operations/unfollowList.md) |
| GET | `/2/users/{id}/followers` | Get followers | [View](../operations/getUsersFollowers.md) |
| GET | `/2/users/{id}/following` | Get following | [View](../operations/getUsersFollowing.md) |
| POST | `/2/users/{id}/following` | Follow User | [View](../operations/followUser.md) |
| GET | `/2/users/{id}/liked_tweets` | Get liked Posts | [View](../operations/getUsersLikedPosts.md) |
| POST | `/2/users/{id}/likes` | Like Post | [View](../operations/likePost.md) |
| DELETE | `/2/users/{id}/likes/{tweet_id}` | Unlike Post | [View](../operations/unlikePost.md) |
| GET | `/2/users/{id}/list_memberships` | Get List memberships | [View](../operations/getUsersListMemberships.md) |
| GET | `/2/users/{id}/mentions` | Get mentions | [View](../operations/getUsersMentions.md) |
| GET | `/2/users/{id}/muting` | Get muting | [View](../operations/getUsersMuting.md) |
| POST | `/2/users/{id}/muting` | Mute User | [View](../operations/muteUser.md) |
| GET | `/2/users/{id}/owned_lists` | Get owned Lists | [View](../operations/getUsersOwnedLists.md) |
| GET | `/2/users/{id}/pinned_lists` | Get pinned Lists | [View](../operations/getUsersPinnedLists.md) |
| POST | `/2/users/{id}/pinned_lists` | Pin List | [View](../operations/pinList.md) |
| DELETE | `/2/users/{id}/pinned_lists/{list_id}` | Unpin List | [View](../operations/unpinList.md) |
| POST | `/2/users/{id}/retweets` | Repost Post | [View](../operations/repostPost.md) |
| DELETE | `/2/users/{id}/retweets/{source_tweet_id}` | Unrepost Post | [View](../operations/unrepostPost.md) |
| GET | `/2/users/{id}/timelines/reverse_chronological` | Get Timeline | [View](../operations/getUsersTimeline.md) |
| GET | `/2/users/{id}/tweets` | Get Posts | [View](../operations/getUsersPosts.md) |
| DELETE | `/2/users/{source_user_id}/following/{target_user_id}` | Unfollow User | [View](../operations/unfollowUser.md) |
| DELETE | `/2/users/{source_user_id}/muting/{target_user_id}` | Unmute User | [View](../operations/unmuteUser.md) |

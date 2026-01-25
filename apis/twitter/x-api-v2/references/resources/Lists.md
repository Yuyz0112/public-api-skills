# Lists

Endpoints related to retrieving, managing Lists

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| POST | `/2/lists` | Create List | [View](../operations/createLists.md) |
| GET | `/2/lists/{id}` | Get List by ID | [View](../operations/getListsById.md) |
| PUT | `/2/lists/{id}` | Update List | [View](../operations/updateLists.md) |
| DELETE | `/2/lists/{id}` | Delete List | [View](../operations/deleteLists.md) |
| GET | `/2/lists/{id}/followers` | Get List followers | [View](../operations/getListsFollowers.md) |
| GET | `/2/lists/{id}/members` | Get List members | [View](../operations/getListsMembers.md) |
| POST | `/2/lists/{id}/members` | Add List member | [View](../operations/addListsMember.md) |
| DELETE | `/2/lists/{id}/members/{user_id}` | Remove List member | [View](../operations/removeListsMemberByUserId.md) |
| GET | `/2/lists/{id}/tweets` | Get List Posts | [View](../operations/getListsPosts.md) |
| GET | `/2/users/{id}/followed_lists` | Get followed Lists | [View](../operations/getUsersFollowedLists.md) |
| POST | `/2/users/{id}/followed_lists` | Follow List | [View](../operations/followList.md) |
| DELETE | `/2/users/{id}/followed_lists/{list_id}` | Unfollow List | [View](../operations/unfollowList.md) |
| GET | `/2/users/{id}/list_memberships` | Get List memberships | [View](../operations/getUsersListMemberships.md) |
| GET | `/2/users/{id}/owned_lists` | Get owned Lists | [View](../operations/getUsersOwnedLists.md) |
| GET | `/2/users/{id}/pinned_lists` | Get pinned Lists | [View](../operations/getUsersPinnedLists.md) |
| POST | `/2/users/{id}/pinned_lists` | Pin List | [View](../operations/pinList.md) |
| DELETE | `/2/users/{id}/pinned_lists/{list_id}` | Unpin List | [View](../operations/unpinList.md) |

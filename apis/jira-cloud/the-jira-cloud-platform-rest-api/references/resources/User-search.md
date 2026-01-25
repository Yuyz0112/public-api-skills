# User search

This resource represents various ways to search for and find users. Use it to obtain list of users including users assignable to projects and issues, users with permissions, user lists for pickup fields, and user lists generated using structured queries. Note that the operations in this resource only return users found within the first 1000 users.

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/rest/api/3/user/assignable/multiProjectSearch` | Find users assignable to projects | [View](../operations/findBulkAssignableUsers.md) |
| GET | `/rest/api/3/user/assignable/search` | Find users assignable to issues | [View](../operations/findAssignableUsers.md) |
| GET | `/rest/api/3/user/permission/search` | Find users with permissions | [View](../operations/findUsersWithAllPermissions.md) |
| GET | `/rest/api/3/user/picker` | Find users for picker | [View](../operations/findUsersForPicker.md) |
| GET | `/rest/api/3/user/search` | Find users | [View](../operations/findUsers.md) |
| GET | `/rest/api/3/user/search/query` | Find users by query | [View](../operations/findUsersByQuery.md) |
| GET | `/rest/api/3/user/search/query/key` | Find user keys by query | [View](../operations/findUserKeysByQuery.md) |
| GET | `/rest/api/3/user/viewissue/search` | Find users with browse permission | [View](../operations/findUsersWithBrowsePermission.md) |

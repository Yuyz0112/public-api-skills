# Users

This resource represent users. Use it to:

 *  get, get a list of, create, and delete users.
 *  get, set, and reset a user's default issue table columns.
 *  get a list of the groups the user belongs to.
 *  get a list of user account IDs for a list of usernames or user keys.

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/rest/api/3/user` | Get user | [View](../operations/getUser.md) |
| POST | `/rest/api/3/user` | Create user | [View](../operations/createUser.md) |
| DELETE | `/rest/api/3/user` | Delete user | [View](../operations/removeUser.md) |
| GET | `/rest/api/3/user/bulk` | Bulk get users | [View](../operations/bulkGetUsers.md) |
| GET | `/rest/api/3/user/bulk/migration` | Get account IDs for users | [View](../operations/bulkGetUsersMigration.md) |
| GET | `/rest/api/3/user/columns` | Get user default columns | [View](../operations/getUserDefaultColumns.md) |
| PUT | `/rest/api/3/user/columns` | Set user default columns | [View](../operations/setUserColumns.md) |
| DELETE | `/rest/api/3/user/columns` | Reset user default columns | [View](../operations/resetUserColumns.md) |
| GET | `/rest/api/3/user/email` | Get user email | [View](../operations/getUserEmail.md) |
| GET | `/rest/api/3/user/email/bulk` | Get user email bulk | [View](../operations/getUserEmailBulk.md) |
| GET | `/rest/api/3/user/groups` | Get user groups | [View](../operations/getUserGroups.md) |
| GET | `/rest/api/3/users` | Get all users default | [View](../operations/getAllUsersDefault.md) |
| GET | `/rest/api/3/users/search` | Get all users | [View](../operations/getAllUsers.md) |

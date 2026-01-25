# Groups

This resource represents groups of users. Use it to get, create, find, and delete groups as well as add and remove users from groups. (\[WARNING\] The standard Atlassian group names are default names only and can be edited or deleted. For example, an admin or Atlassian support could delete the default group jira-software-users or rename it to jsw-users at any point. See https://support.atlassian.com/user-management/docs/create-and-update-groups/ for details.)

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/rest/api/3/group` | Get group | [View](../operations/getGroup.md) |
| POST | `/rest/api/3/group` | Create group | [View](../operations/createGroup.md) |
| DELETE | `/rest/api/3/group` | Remove group | [View](../operations/removeGroup.md) |
| GET | `/rest/api/3/group/bulk` | Bulk get groups | [View](../operations/bulkGetGroups.md) |
| GET | `/rest/api/3/group/member` | Get users from group | [View](../operations/getUsersFromGroup.md) |
| POST | `/rest/api/3/group/user` | Add user to group | [View](../operations/addUserToGroup.md) |
| DELETE | `/rest/api/3/group/user` | Remove user from group | [View](../operations/removeUserFromGroup.md) |
| GET | `/rest/api/3/groups/picker` | Find groups | [View](../operations/findGroups.md) |

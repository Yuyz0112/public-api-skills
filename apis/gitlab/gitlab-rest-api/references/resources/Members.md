# Members

Operations related to members.

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/api/v4/groups/{id}/members` | Gets a list of group or project members viewable by the authenticated user. | [View](../operations/getApiV4GroupsIdMembers.md) |
| POST | `/api/v4/groups/{id}/members` | Adds a member to a group or project. | [View](../operations/postApiV4GroupsIdMembers.md) |
| GET | `/api/v4/groups/{id}/members/all` | Gets a list of group or project members viewable by the authenticated user, including those who gained membership through ancestor group. | [View](../operations/getApiV4GroupsIdMembersAll.md) |
| GET | `/api/v4/groups/{id}/members/{user_id}` | Gets a member of a group or project. | [View](../operations/getApiV4GroupsIdMembersUserId.md) |
| PUT | `/api/v4/groups/{id}/members/{user_id}` | Updates a member of a group or project. | [View](../operations/putApiV4GroupsIdMembersUserId.md) |
| DELETE | `/api/v4/groups/{id}/members/{user_id}` | Removes a user from a group or project. | [View](../operations/deleteApiV4GroupsIdMembersUserId.md) |
| GET | `/api/v4/groups/{id}/members/all/{user_id}` | Gets a member of a group or project, including those who gained membership through ancestor group | [View](../operations/getApiV4GroupsIdMembersAllUserId.md) |
| GET | `/api/v4/projects/{id}/members` | Gets a list of group or project members viewable by the authenticated user. | [View](../operations/getApiV4ProjectsIdMembers.md) |
| POST | `/api/v4/projects/{id}/members` | Adds a member to a group or project. | [View](../operations/postApiV4ProjectsIdMembers.md) |
| GET | `/api/v4/projects/{id}/members/all` | Gets a list of group or project members viewable by the authenticated user, including those who gained membership through ancestor group. | [View](../operations/getApiV4ProjectsIdMembersAll.md) |
| GET | `/api/v4/projects/{id}/members/{user_id}` | Gets a member of a group or project. | [View](../operations/getApiV4ProjectsIdMembersUserId.md) |
| PUT | `/api/v4/projects/{id}/members/{user_id}` | Updates a member of a group or project. | [View](../operations/putApiV4ProjectsIdMembersUserId.md) |
| DELETE | `/api/v4/projects/{id}/members/{user_id}` | Removes a user from a group or project. | [View](../operations/deleteApiV4ProjectsIdMembersUserId.md) |
| GET | `/api/v4/projects/{id}/members/all/{user_id}` | Gets a member of a group or project, including those who gained membership through ancestor group | [View](../operations/getApiV4ProjectsIdMembersAllUserId.md) |
| POST | `/api/v4/groups/{id}/members/{user_id}/override` | Overrides the access level of an LDAP group member. | [View](../operations/postApiV4GroupsIdMembersUserIdOverride.md) |
| DELETE | `/api/v4/groups/{id}/members/{user_id}/override` | Remove an LDAP group member access level override. | [View](../operations/deleteApiV4GroupsIdMembersUserIdOverride.md) |
| PUT | `/api/v4/groups/{id}/members/{member_id}/approve` | Approves a pending member | [View](../operations/putApiV4GroupsIdMembersMemberIdApprove.md) |
| POST | `/api/v4/groups/{id}/members/approve_all` | Approves all pending members | [View](../operations/postApiV4GroupsIdMembersApproveAll.md) |
| GET | `/api/v4/groups/{id}/pending_members` | Lists all pending members for a group including invited users | [View](../operations/getApiV4GroupsIdPendingMembers.md) |
| PUT | `/api/v4/groups/{id}/members/{user_id}/state` | Changes the state of the memberships of a user in the group | [View](../operations/putApiV4GroupsIdMembersUserIdState.md) |
| GET | `/api/v4/groups/{id}/billable_members/{user_id}/memberships` | Get the direct memberships of a billable user of a top-level group. | [View](../operations/getApiV4GroupsIdBillableMembersUserIdMemberships.md) |
| GET | `/api/v4/groups/{id}/billable_members/{user_id}/indirect` | Get the indirect memberships of a billable user of a top-level group. | [View](../operations/getApiV4GroupsIdBillableMembersUserIdIndirect.md) |
| DELETE | `/api/v4/groups/{id}/billable_members/{user_id}` | Removes a billable member from a group or project. | [View](../operations/deleteApiV4GroupsIdBillableMembersUserId.md) |

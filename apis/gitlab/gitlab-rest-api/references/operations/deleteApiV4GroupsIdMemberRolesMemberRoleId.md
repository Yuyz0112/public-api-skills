# DELETE /api/v4/groups/{id}/member_roles/{member_role_id}

**Resource:** [Group member roles](../resources/Group-member-roles.md)
**Delete Member Role for a group**
**Operation ID:** `deleteApiV4GroupsIdMemberRolesMemberRoleId`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the group |
| `member_role_id` | path | integer | Yes | The ID of the Group-Member Role to be deleted |

## Responses

| Status | Description |
|--------|-------------|
| 204 | No Content |
| 400 | Bad Request |
| 401 | Unauthorized |
| 404 | 404 Member Role Not Found |


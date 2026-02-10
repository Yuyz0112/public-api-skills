# GET /api/v4/groups/{id}/member_roles

**Resource:** [Group member roles](../resources/Group-member-roles.md)
**Get Member Roles for a group**
**Operation ID:** `getApiV4GroupsIdMemberRoles`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the group |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[APIEntitiesMemberRole](../schemas/APIEntitiesMemberRole/APIEntitiesMemberRole.md)


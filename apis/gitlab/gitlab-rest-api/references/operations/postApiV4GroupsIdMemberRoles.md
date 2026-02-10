# POST /api/v4/groups/{id}/member_roles

**Resource:** [Group member roles](../resources/Group-member-roles.md)
**Create Member Role for a group**
**Operation ID:** `postApiV4GroupsIdMemberRoles`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the group |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Created |
| 400 | Bad Request |
| 401 | Unauthorized |

**Success Response Schema:**

[APIEntitiesMemberRole](../schemas/APIEntitiesMemberRole/APIEntitiesMemberRole.md)


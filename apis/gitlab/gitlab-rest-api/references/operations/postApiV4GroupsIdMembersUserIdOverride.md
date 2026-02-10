# POST /api/v4/groups/{id}/members/{user_id}/override

**Resource:** [Members](../resources/Members.md)
**Overrides the access level of an LDAP group member.**
**Operation ID:** `postApiV4GroupsIdMembersUserIdOverride`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The ID of a group |
| `user_id` | path | integer | Yes | The user ID of the member |

## Responses

| Status | Description |
|--------|-------------|
| 201 | Created |

**Success Response Schema:**

[APIEntitiesMember](../schemas/APIEntitiesMember/APIEntitiesMember.md)


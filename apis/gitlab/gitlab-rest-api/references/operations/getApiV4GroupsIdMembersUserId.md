# GET /api/v4/groups/{id}/members/{user_id}

**Resource:** [Members](../resources/Members.md)
**Gets a member of a group or project.**
**Operation ID:** `getApiV4GroupsIdMembersUserId`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The group ID |
| `user_id` | path | integer | Yes | The user ID of the member |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[APIEntitiesMember](../schemas/APIEntitiesMember/APIEntitiesMember.md)


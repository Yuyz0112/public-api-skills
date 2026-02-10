# GET /api/v4/projects/{id}/members/all/{user_id}

**Resource:** [Members](../resources/Members.md)
**Gets a member of a group or project, including those who gained membership through ancestor group**
**Operation ID:** `getApiV4ProjectsIdMembersAllUserId`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The project ID |
| `user_id` | path | integer | Yes | The user ID of the member |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[APIEntitiesMember](../schemas/APIEntitiesMember/APIEntitiesMember.md)


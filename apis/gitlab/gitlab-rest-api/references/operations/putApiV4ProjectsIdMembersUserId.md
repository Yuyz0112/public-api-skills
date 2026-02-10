# PUT /api/v4/projects/{id}/members/{user_id}

**Resource:** [Members](../resources/Members.md)
**Updates a member of a group or project.**
**Operation ID:** `putApiV4ProjectsIdMembersUserId`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The project ID |
| `user_id` | path | integer | Yes | The user ID of the new member |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[APIEntitiesMember](../schemas/APIEntitiesMember/APIEntitiesMember.md)


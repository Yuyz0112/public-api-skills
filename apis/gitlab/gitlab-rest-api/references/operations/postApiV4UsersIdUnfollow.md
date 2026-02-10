# POST /api/v4/users/{id}/unfollow

**Resource:** [Users](../resources/Users.md)
**Unfollow a user**
**Operation ID:** `postApiV4UsersIdUnfollow`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | integer | Yes | The ID of the user |

## Responses

| Status | Description |
|--------|-------------|
| 201 | Created |

**Success Response Schema:**

[APIEntitiesUser](../schemas/APIEntitiesUser/APIEntitiesUser.md)


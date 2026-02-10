# POST /api/v4/users/{id}/follow

**Resource:** [Users](../resources/Users.md)
**Follow a user**
**Operation ID:** `postApiV4UsersIdFollow`

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


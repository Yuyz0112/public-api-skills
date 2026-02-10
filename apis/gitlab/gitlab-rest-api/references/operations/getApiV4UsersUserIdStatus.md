# GET /api/v4/users/{user_id}/status

**Resource:** [Users](../resources/Users.md)
**Get the status of a user**
**Operation ID:** `getApiV4UsersUserIdStatus`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `user_id` | path | string | Yes | The ID or username of the user |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[APIEntitiesUserStatus](../schemas/APIEntitiesUserStatus/APIEntitiesUserStatus.md)


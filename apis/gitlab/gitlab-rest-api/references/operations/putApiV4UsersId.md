# PUT /api/v4/users/{id}

**Resource:** [Users](../resources/Users.md)
**Update a user. Available only for admins.**
**Operation ID:** `putApiV4UsersId`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | integer | Yes | The ID of the user |

## Request Body

**Content Types:** `multipart/form-data`

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[APIEntitiesUserWithAdmin](../schemas/APIEntitiesUserWithAdmin/APIEntitiesUserWithAdmin.md)


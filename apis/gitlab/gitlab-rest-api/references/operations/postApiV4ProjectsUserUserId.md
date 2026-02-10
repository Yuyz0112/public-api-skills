# POST /api/v4/projects/user/{user_id}

**Resource:** [Projects](../resources/Projects.md)
**Create new project for a specified user. Only available to admin users.**
**Operation ID:** `postApiV4ProjectsUserUserId`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `user_id` | path | integer | Yes | The ID of a user |

## Request Body

**Required:** Yes

**Content Types:** `multipart/form-data`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Created |
| 400 | Bad request |
| 403 | Unauthenticated |
| 404 | Not found |

**Success Response Schema:**

[APIEntitiesProject](../schemas/APIEntitiesProject/APIEntitiesProject.md)


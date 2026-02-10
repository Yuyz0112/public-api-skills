# GET /api/v4/users/{id}/following

**Resource:** [Users](../resources/Users.md)
**Get the users who follow a user**
**Operation ID:** `getApiV4UsersIdFollowing`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | integer | Yes | The ID of the user |
| `page` | query | integer | No | Current page number |
| `per_page` | query | integer | No | Number of items per page |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[APIEntitiesUserBasic](../schemas/APIEntitiesUserBasic/APIEntitiesUserBasic.md)


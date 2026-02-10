# GET /api/v4/users/{id}/emails

**Resource:** [Users](../resources/Users.md)
**Get the emails addresses of a specified user. Available only for admins.**
**Operation ID:** `getApiV4UsersIdEmails`

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

[APIEntitiesEmail](../schemas/APIEntitiesEmail/APIEntitiesEmail.md)


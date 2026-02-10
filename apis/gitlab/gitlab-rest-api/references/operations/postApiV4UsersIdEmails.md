# POST /api/v4/users/{id}/emails

**Resource:** [Users](../resources/Users.md)
**Add an email address to a specified user. Available only for admins.**
**Operation ID:** `postApiV4UsersIdEmails`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | integer | Yes | The ID of the user |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Created |

**Success Response Schema:**

[APIEntitiesEmail](../schemas/APIEntitiesEmail/APIEntitiesEmail.md)


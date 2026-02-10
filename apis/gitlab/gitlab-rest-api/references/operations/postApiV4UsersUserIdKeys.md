# POST /api/v4/users/{user_id}/keys

**Resource:** [Keys](../resources/Keys.md)
**Add an SSH key to a specified user. Available only for admins.**
**Operation ID:** `postApiV4UsersUserIdKeys`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `user_id` | path | integer | Yes | The ID of the user |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Created |

**Success Response Schema:**

[APIEntitiesSSHKey](../schemas/APIEntitiesSSHKey/APIEntitiesSSHKey.md)


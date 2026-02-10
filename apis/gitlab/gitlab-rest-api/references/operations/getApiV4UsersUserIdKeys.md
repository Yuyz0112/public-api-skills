# GET /api/v4/users/{user_id}/keys

**Resource:** [Keys](../resources/Keys.md)
**Get the SSH keys of a specified user.**
**Operation ID:** `getApiV4UsersUserIdKeys`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `user_id` | path | string | Yes | The ID or username of the user |
| `page` | query | integer | No | Current page number |
| `per_page` | query | integer | No | Number of items per page |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[APIEntitiesSSHKey](../schemas/APIEntitiesSSHKey/APIEntitiesSSHKey.md)


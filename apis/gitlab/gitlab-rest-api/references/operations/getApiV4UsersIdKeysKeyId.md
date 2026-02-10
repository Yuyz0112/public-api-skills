# GET /api/v4/users/{id}/keys/{key_id}

**Resource:** [Keys](../resources/Keys.md)
**Get a SSH key of a specified user.**
**Operation ID:** `getApiV4UsersIdKeysKeyId`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | integer | Yes | The ID of the user |
| `key_id` | path | integer | Yes | The ID of the SSH key |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[APIEntitiesSSHKey](../schemas/APIEntitiesSSHKey/APIEntitiesSSHKey.md)


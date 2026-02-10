# DELETE /api/v4/users/{id}/keys/{key_id}

**Resource:** [Keys](../resources/Keys.md)
**Delete an existing SSH key from a specified user. Available only for admins.**
**Operation ID:** `deleteApiV4UsersIdKeysKeyId`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | integer | Yes | The ID of the user |
| `key_id` | path | integer | Yes | The ID of the SSH key |

## Responses

| Status | Description |
|--------|-------------|
| 204 | No Content |


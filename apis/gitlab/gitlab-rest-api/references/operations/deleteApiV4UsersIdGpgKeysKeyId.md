# DELETE /api/v4/users/{id}/gpg_keys/{key_id}

**Resource:** [Keys](../resources/Keys.md)
**Delete an existing GPG key from a specified user. Available only for admins.**
**Operation ID:** `deleteApiV4UsersIdGpgKeysKeyId`

This feature was added in GitLab 10.0

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | integer | Yes | The ID of the user |
| `key_id` | path | integer | Yes | The ID of the GPG key |

## Responses

| Status | Description |
|--------|-------------|
| 204 | No Content |


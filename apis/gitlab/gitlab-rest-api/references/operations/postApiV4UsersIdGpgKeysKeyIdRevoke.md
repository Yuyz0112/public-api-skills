# POST /api/v4/users/{id}/gpg_keys/{key_id}/revoke

**Resource:** [Keys](../resources/Keys.md)
**Revokes an existing GPG key from a specified user. Available only for admins.**
**Operation ID:** `postApiV4UsersIdGpgKeysKeyIdRevoke`

This feature was added in GitLab 10.0

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | integer | Yes | The ID of the user |
| `key_id` | path | integer | Yes | The ID of the GPG key |

## Responses

| Status | Description |
|--------|-------------|
| 201 | Created |


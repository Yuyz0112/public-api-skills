# GET /api/v4/users/{id}/gpg_keys/{key_id}

**Resource:** [Keys](../resources/Keys.md)
**Get a specific GPG key for a given user.**
**Operation ID:** `getApiV4UsersIdGpgKeysKeyId`

This feature was added in GitLab 13.5

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | integer | Yes | The ID of the user |
| `key_id` | path | integer | Yes | The ID of the GPG key |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[APIEntitiesGpgKey](../schemas/APIEntitiesGpgKey/APIEntitiesGpgKey.md)


# POST /api/v4/users/{id}/gpg_keys

**Resource:** [Keys](../resources/Keys.md)
**Add a GPG key to a specified user. Available only for admins.**
**Operation ID:** `postApiV4UsersIdGpgKeys`

This feature was added in GitLab 10.0

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

[APIEntitiesGpgKey](../schemas/APIEntitiesGpgKey/APIEntitiesGpgKey.md)


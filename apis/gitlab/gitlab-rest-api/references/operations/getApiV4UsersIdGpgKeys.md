# GET /api/v4/users/{id}/gpg_keys

**Resource:** [Keys](../resources/Keys.md)
**Get the GPG keys of a specified user.**
**Operation ID:** `getApiV4UsersIdGpgKeys`

This feature was added in GitLab 10.0

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

[APIEntitiesGpgKey](../schemas/APIEntitiesGpgKey/APIEntitiesGpgKey.md)


# GET /api/v4/user/gpg_keys/{key_id}

**Resource:** [Keys](../resources/Keys.md)
**Get a single GPG key owned by currently authenticated user**
**Operation ID:** `getApiV4UserGpgKeysKeyId`

This feature was added in GitLab 10.0

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `key_id` | path | integer | Yes | The ID of the GPG key |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[APIEntitiesGpgKey](../schemas/APIEntitiesGpgKey/APIEntitiesGpgKey.md)


# POST /api/v4/user/gpg_keys

**Resource:** [Keys](../resources/Keys.md)
**Add a new GPG key to the currently authenticated user**
**Operation ID:** `postApiV4UserGpgKeys`

This feature was added in GitLab 10.0

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Created |

**Success Response Schema:**

[APIEntitiesGpgKey](../schemas/APIEntitiesGpgKey/APIEntitiesGpgKey.md)


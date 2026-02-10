# GET /api/v4/user/gpg_keys

**Resource:** [Keys](../resources/Keys.md)
**Get the currently authenticated user's GPG keys**
**Operation ID:** `getApiV4UserGpgKeys`

This feature was added in GitLab 10.0

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `page` | query | integer | No | Current page number |
| `per_page` | query | integer | No | Number of items per page |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[APIEntitiesGpgKey](../schemas/APIEntitiesGpgKey/APIEntitiesGpgKey.md)


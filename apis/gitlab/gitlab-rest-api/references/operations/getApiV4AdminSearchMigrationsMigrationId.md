# GET /api/v4/admin/search/migrations/{migration_id}

**Resource:** [Search](../resources/Search.md)
**Get a migration by version or name**
**Operation ID:** `getApiV4AdminSearchMigrationsMigrationId`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `migration_id` | path | any | Yes | The version or name of the search migration |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | 401 Unauthorized |
| 403 | 403 Forbidden |
| 404 | 404 Not found |

**Success Response Schema:**

[APIEntitiesSearchMigration](../schemas/APIEntitiesSearchMigration/APIEntitiesSearchMigration.md)


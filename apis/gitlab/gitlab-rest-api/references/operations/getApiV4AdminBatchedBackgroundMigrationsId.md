# GET /api/v4/admin/batched_background_migrations/{id}

**Resource:** [Batched background migrations](../resources/Batched-background-migrations.md)
**Retrieve a batched background migration**
**Operation ID:** `getApiV4AdminBatchedBackgroundMigrationsId`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `database` | query | enum: main, ci, sec... | No | The name of the database |
| `id` | path | integer | Yes | The batched background migration id |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | 401 Unauthorized |
| 403 | 403 Forbidden |
| 404 | 404 Not found |

**Success Response Schema:**

[APIEntitiesBatchedBackgroundMigration](../schemas/APIEntitiesBatchedBackgroundMigration/APIEntitiesBatchedBackgroundMigration.md)


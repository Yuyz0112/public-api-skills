# GET /api/v4/admin/batched_background_migrations

**Resource:** [Batched background migrations](../resources/Batched-background-migrations.md)
**Get the list of batched background migrations**
**Operation ID:** `getApiV4AdminBatchedBackgroundMigrations`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `database` | query | enum: main, ci, sec... | No | The name of the database, the default `main` |
| `job_class_name` | query | string | No | Filter migrations by job class name. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | 401 Unauthorized |
| 403 | 403 Forbidden |

**Success Response Schema:**

[APIEntitiesBatchedBackgroundMigration](../schemas/APIEntitiesBatchedBackgroundMigration/APIEntitiesBatchedBackgroundMigration.md)


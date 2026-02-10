# PUT /api/v4/admin/batched_background_migrations/{id}/resume

**Resource:** [Batched background migrations](../resources/Batched-background-migrations.md)
**Resume a batched background migration**
**Operation ID:** `putApiV4AdminBatchedBackgroundMigrationsIdResume`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | integer | Yes | The batched background migration id |

## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | 401 Unauthorized |
| 403 | 403 Forbidden |
| 404 | 404 Not found |
| 422 | You can resume only `paused` batched background migrations. |

**Success Response Schema:**

[APIEntitiesBatchedBackgroundMigration](../schemas/APIEntitiesBatchedBackgroundMigration/APIEntitiesBatchedBackgroundMigration.md)


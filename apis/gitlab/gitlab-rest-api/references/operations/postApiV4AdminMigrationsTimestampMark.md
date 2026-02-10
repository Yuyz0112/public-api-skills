# POST /api/v4/admin/migrations/{timestamp}/mark

**Resource:** [Migrations](../resources/Migrations.md)
**Mark the migration as successfully executed**
**Operation ID:** `postApiV4AdminMigrationsTimestampMark`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `timestamp` | path | integer | Yes | The migration version timestamp |

## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | 201 Created |
| 401 | 401 Unauthorized |
| 403 | 403 Forbidden |
| 404 | 404 Not found |
| 422 | You can mark only pending migrations |


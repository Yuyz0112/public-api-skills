# GET /orgs/{org}/migrations/{migration_id}

**Resource:** [migrations](../resources/migrations.md)
**Get an organization migration status**
**Operation ID:** `migrations/get-status-for-org`

Fetches the status of a migration.

The `state` of a migration can be one of the following values:

*   `pending`, which means the migration hasn't started yet.
*   `exporting`, which means the migration is in progress.
*   `exported`, which means the migration finished successfully.
*   `failed`, which means the migration failed.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `exclude` | query | string[] | No | Exclude attributes from the API response to improve performance |

## Responses

| Status | Description |
|--------|-------------|
| 200 | *   `pending`, which means the migration hasn't started yet.
*   `exporting`, which means the migration is in progress.
*   `exported`, which means the migration finished successfully.
*   `failed`, which means the migration failed. |
| 404 | (reference) |

**Success Response Schema:**

[migration](../schemas/migration/migration.md)


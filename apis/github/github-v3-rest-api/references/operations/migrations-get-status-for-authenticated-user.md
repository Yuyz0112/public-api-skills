# GET /user/migrations/{migration_id}

**Resource:** [migrations](../resources/migrations.md)
**Get a user migration status**
**Operation ID:** `migrations/get-status-for-authenticated-user`

Fetches a single user migration. The response includes the `state` of the migration, which can be one of the following values:

*   `pending` - the migration hasn't started yet.
*   `exporting` - the migration is in progress.
*   `exported` - the migration finished successfully.
*   `failed` - the migration failed.

Once the migration has been `exported` you can [download the migration archive](https://docs.github.com/rest/migrations/users#download-a-user-migration-archive).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `exclude` | query | string[] | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 304 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[migration](../schemas/migration/migration.md)


# GET /user/migrations

**Resource:** [migrations](../resources/migrations.md)
**List user migrations**
**Operation ID:** `migrations/list-for-authenticated-user`

Lists all migrations a user has started.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 304 | (reference) |
| 401 | (reference) |
| 403 | (reference) |

**Success Response Schema:**

Array of [migration](../schemas/migration/migration.md)


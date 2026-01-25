# GET /user/migrations/{migration_id}/repositories

**Resource:** [migrations](../resources/migrations.md)
**List repositories for a user migration**
**Operation ID:** `migrations/list-repos-for-authenticated-user`

Lists all the repositories for this user migration.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 404 | (reference) |

**Success Response Schema:**

Array of [minimal-repository](../schemas/minimal-repository/minimal-repository.md)


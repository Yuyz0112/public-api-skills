# GET /orgs/{org}/migrations/{migration_id}/repositories

**Resource:** [migrations](../resources/migrations.md)
**List repositories in an organization migration**
**Operation ID:** `migrations/list-repos-for-org`

List all the repositories for this organization migration.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 404 | (reference) |

**Success Response Schema:**

Array of [minimal-repository](../schemas/minimal-repository/minimal-repository.md)


# POST /orgs/{org}/migrations

**Resource:** [migrations](../resources/migrations.md)
**Start an organization migration**
**Operation ID:** `migrations/start-for-org`

Initiates the generation of a migration archive.

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Response |
| 404 | (reference) |
| 422 | (reference) |

**Success Response Schema:**

[migration](../schemas/migration/migration.md)


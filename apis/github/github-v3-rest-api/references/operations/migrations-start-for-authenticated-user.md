# POST /user/migrations

**Resource:** [migrations](../resources/migrations.md)
**Start a user migration**
**Operation ID:** `migrations/start-for-authenticated-user`

Initiates the generation of a user migration archive.

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Response |
| 304 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 422 | (reference) |

**Success Response Schema:**

[migration](../schemas/migration/migration.md)


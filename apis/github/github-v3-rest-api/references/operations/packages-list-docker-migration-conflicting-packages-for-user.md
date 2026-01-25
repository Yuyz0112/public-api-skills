# GET /users/{username}/docker/conflicts

**Resource:** [packages](../resources/packages.md)
**Get list of conflicting packages during Docker migration for user**
**Operation ID:** `packages/list-docker-migration-conflicting-packages-for-user`

Lists all packages that are in a specific user's namespace, that the requesting user has access to, and that encountered a conflict during Docker migration.

OAuth app tokens and personal access tokens (classic) need the `read:packages` scope to use this endpoint.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 401 | (reference) |
| 403 | (reference) |

**Success Response Schema:**

Array of [package](../schemas/package/package.md)


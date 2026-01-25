# GET /user/docker/conflicts

**Resource:** [packages](../resources/packages.md)
**Get list of conflicting packages during Docker migration for authenticated-user**
**Operation ID:** `packages/list-docker-migration-conflicting-packages-for-authenticated-user`

Lists all packages that are owned by the authenticated user within the user's namespace, and that encountered a conflict during a Docker migration.

OAuth app tokens and personal access tokens (classic) need the `read:packages` scope to use this endpoint.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |

**Success Response Schema:**

Array of [package](../schemas/package/package.md)


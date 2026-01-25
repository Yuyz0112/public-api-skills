# GET /orgs/{org}/docker/conflicts

**Resource:** [packages](../resources/packages.md)
**Get list of conflicting packages during Docker migration for organization**
**Operation ID:** `packages/list-docker-migration-conflicting-packages-for-organization`

Lists all packages that are in a specific organization, are readable by the requesting user, and that encountered a conflict during a Docker migration.

OAuth app tokens and personal access tokens (classic) need the `read:packages` scope to use this endpoint.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 401 | (reference) |
| 403 | (reference) |

**Success Response Schema:**

Array of [package](../schemas/package/package.md)


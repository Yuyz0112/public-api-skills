# POST /api/v4/bulk_imports

**Resource:** [Imports](../resources/Imports.md)
**Start a new GitLab Migration**
**Operation ID:** `postApiV4BulkImports`

This feature was introduced in GitLab 14.2.

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Bad request |
| 401 | Unauthorized |
| 404 | Not found |
| 422 | Unprocessable entity |
| 503 | Service unavailable |

**Success Response Schema:**

[APIEntitiesBulkImport](../schemas/APIEntitiesBulkImport/APIEntitiesBulkImport.md)


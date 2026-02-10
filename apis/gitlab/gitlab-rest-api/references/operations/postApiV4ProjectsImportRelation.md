# POST /api/v4/projects/import-relation

**Resource:** [Project import](../resources/Project-import.md)
**Re-import a relation into a project**
**Operation ID:** `postApiV4ProjectsImportRelation`

This feature was introduced in GitLab 16.11.

## Request Body

**Required:** Yes

**Content Types:** `multipart/form-data`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Created |
| 400 | Bad request |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not found |
| 503 | Service unavailable |

**Success Response Schema:**

[APIEntitiesRelationImportTracker](../schemas/APIEntitiesRelationImportTracker/APIEntitiesRelationImportTracker.md)


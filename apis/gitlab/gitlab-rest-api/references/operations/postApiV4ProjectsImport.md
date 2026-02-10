# POST /api/v4/projects/import

**Resource:** [Project import](../resources/Project-import.md)
**Create a new project import**
**Operation ID:** `postApiV4ProjectsImport`

This feature was introduced in GitLab 10.6.

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

[APIEntitiesProjectImportStatus](../schemas/APIEntitiesProjectImportStatus/APIEntitiesProjectImportStatus.md)


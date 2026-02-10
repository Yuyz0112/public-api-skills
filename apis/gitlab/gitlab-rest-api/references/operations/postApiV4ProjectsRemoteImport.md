# POST /api/v4/projects/remote-import

**Resource:** [Project import](../resources/Project-import.md)
**Create a new project import using a remote object storage path**
**Operation ID:** `postApiV4ProjectsRemoteImport`

This feature was introduced in GitLab 13.2.

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Created |
| 400 | Bad request |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not found |
| 429 | Too many requests |
| 503 | Service unavailable |

**Success Response Schema:**

[APIEntitiesProjectImportStatus](../schemas/APIEntitiesProjectImportStatus/APIEntitiesProjectImportStatus.md)


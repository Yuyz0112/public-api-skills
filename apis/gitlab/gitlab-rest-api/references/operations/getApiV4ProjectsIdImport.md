# GET /api/v4/projects/{id}/import

**Resource:** [Project import](../resources/Project-import.md)
**Get a project import status**
**Operation ID:** `getApiV4ProjectsIdImport`

This feature was introduced in GitLab 10.6.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Bad request |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not found |
| 503 | Service unavailable |

**Success Response Schema:**

[APIEntitiesProjectImportStatus](../schemas/APIEntitiesProjectImportStatus/APIEntitiesProjectImportStatus.md)


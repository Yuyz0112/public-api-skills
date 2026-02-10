# GET /api/v4/projects/{id}/relation-imports

**Resource:** [Project import](../resources/Project-import.md)
**Get the statuses of relation imports for specified project**
**Operation ID:** `getApiV4ProjectsIdRelationImports`

This feature was introduced in GitLab 16.11.

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


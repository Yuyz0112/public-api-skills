# GET /api/v4/bulk_imports/{import_id}/entities/{entity_id}

**Resource:** [Imports](../resources/Imports.md)
**Get GitLab Migration entity details**
**Operation ID:** `getApiV4BulkImportsImportIdEntitiesEntityId`

This feature was introduced in GitLab 14.1.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `import_id` | path | integer | Yes | The ID of user's GitLab Migration |
| `entity_id` | path | integer | Yes | The ID of GitLab Migration entity |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | Unauthorized |
| 404 | Not found |
| 503 | Service unavailable |

**Success Response Schema:**

[APIEntitiesBulkImportsEntity](../schemas/APIEntitiesBulkImportsEntity/APIEntitiesBulkImportsEntity.md)


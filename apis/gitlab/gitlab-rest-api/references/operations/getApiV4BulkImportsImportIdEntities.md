# GET /api/v4/bulk_imports/{import_id}/entities

**Resource:** [Imports](../resources/Imports.md)
**List GitLab Migration entities**
**Operation ID:** `getApiV4BulkImportsImportIdEntities`

This feature was introduced in GitLab 14.1.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `import_id` | path | integer | Yes | The ID of user's GitLab Migration |
| `status` | query | enum: created, started, finished... | No | Return import entities with specified status |
| `page` | query | integer | No | Current page number |
| `per_page` | query | integer | No | Number of items per page |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | Unauthorized |
| 404 | Not found |
| 503 | Service unavailable |

**Success Response Schema:**

[APIEntitiesBulkImportsEntity](../schemas/APIEntitiesBulkImportsEntity/APIEntitiesBulkImportsEntity.md)


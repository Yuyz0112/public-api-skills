# POST /api/v4/bulk_imports/{import_id}/cancel

**Resource:** [Imports](../resources/Imports.md)
**Cancel GitLab Migration**
**Operation ID:** `postApiV4BulkImportsImportIdCancel`

This feature was introduced in GitLab 17.1

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `import_id` | path | integer | Yes | The ID of user's GitLab Migration |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not found |
| 503 | Service unavailable |

**Success Response Schema:**

[APIEntitiesBulkImport](../schemas/APIEntitiesBulkImport/APIEntitiesBulkImport.md)


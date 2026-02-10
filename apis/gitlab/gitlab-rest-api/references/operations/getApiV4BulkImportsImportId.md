# GET /api/v4/bulk_imports/{import_id}

**Resource:** [Imports](../resources/Imports.md)
**Get GitLab Migration details**
**Operation ID:** `getApiV4BulkImportsImportId`

This feature was introduced in GitLab 14.1.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `import_id` | path | integer | Yes | The ID of user's GitLab Migration |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | Unauthorized |
| 404 | Not found |
| 503 | Service unavailable |

**Success Response Schema:**

[APIEntitiesBulkImport](../schemas/APIEntitiesBulkImport/APIEntitiesBulkImport.md)


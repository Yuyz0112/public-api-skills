# GET /api/v4/projects/{id}/export_relations/status

**Resource:** [Project import](../resources/Project-import.md)
**Relations export status**
**Operation ID:** `getApiV4ProjectsIdExportRelationsStatus`

This feature was introduced in GitLab 14.4

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `relation` | query | string | No | Project relation name |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not found |
| 503 | Service unavailable |

**Success Response Schema:**

[APIEntitiesBulkImportsExportStatus](../schemas/APIEntitiesBulkImportsExportStatus/APIEntitiesBulkImportsExportStatus.md)


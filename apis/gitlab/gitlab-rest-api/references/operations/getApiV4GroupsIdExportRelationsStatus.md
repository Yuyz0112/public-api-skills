# GET /api/v4/groups/{id}/export_relations/status

**Resource:** [Group import and export](../resources/Group-import-and-export.md)
**Relations export status**
**Operation ID:** `getApiV4GroupsIdExportRelationsStatus`

This feature was introduced in GitLab 13.12

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The ID of a group |
| `relation` | query | string | No | Group relation name |

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


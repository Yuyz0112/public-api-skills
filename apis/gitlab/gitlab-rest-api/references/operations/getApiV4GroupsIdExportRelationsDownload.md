# GET /api/v4/groups/{id}/export_relations/download

**Resource:** [Group import and export](../resources/Group-import-and-export.md)
**Download relations export**
**Operation ID:** `getApiV4GroupsIdExportRelationsDownload`

This feature was introduced in GitLab 13.12

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The ID of a group |
| `relation` | query | string | Yes | Group relation name |
| `batched` | query | boolean | No | Whether to download in batches |
| `batch_number` | query | integer | No | Batch number to download |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not found |
| 503 | Service unavailable |


# GET /api/v4/projects/{id}/export_relations/download

**Resource:** [Project import](../resources/Project-import.md)
**Download relations export**
**Operation ID:** `getApiV4ProjectsIdExportRelationsDownload`

This feature was introduced in GitLab 14.4

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `relation` | query | string | Yes | Project relation name |
| `batched` | query | boolean | No | Whether to download in batches |
| `batch_number` | query | integer | No | Batch number to download |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Bad request |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not found |
| 500 | Internal Server Error |
| 503 | Service unavailable |


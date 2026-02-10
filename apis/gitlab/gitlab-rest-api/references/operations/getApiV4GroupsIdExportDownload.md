# GET /api/v4/groups/{id}/export/download

**Resource:** [Group import and export](../resources/Group-import-and-export.md)
**Download export**
**Operation ID:** `getApiV4GroupsIdExportDownload`

This feature was introduced in GitLab 12.5.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The ID of a group |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Bad request |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not found |
| 503 | Service unavailable |


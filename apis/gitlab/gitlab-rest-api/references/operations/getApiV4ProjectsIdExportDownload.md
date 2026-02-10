# GET /api/v4/projects/{id}/export/download

**Resource:** [Project import](../resources/Project-import.md)
**Download export**
**Operation ID:** `getApiV4ProjectsIdExportDownload`

This feature was introduced in GitLab 10.6.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not found |
| 503 | Service unavailable |


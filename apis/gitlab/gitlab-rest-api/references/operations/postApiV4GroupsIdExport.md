# POST /api/v4/groups/{id}/export

**Resource:** [Group import and export](../resources/Group-import-and-export.md)
**Start export**
**Operation ID:** `postApiV4GroupsIdExport`

This feature was introduced in GitLab 12.5.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The ID of a group |

## Responses

| Status | Description |
|--------|-------------|
| 202 | Accepted |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not found |
| 429 | Too many requests |
| 503 | Service unavailable |


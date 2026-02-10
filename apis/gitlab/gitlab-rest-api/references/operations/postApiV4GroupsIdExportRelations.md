# POST /api/v4/groups/{id}/export_relations

**Resource:** [Group import and export](../resources/Group-import-and-export.md)
**Start relations export**
**Operation ID:** `postApiV4GroupsIdExportRelations`

This feature was introduced in GitLab 13.12

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The ID of a group |

## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 202 | Accepted |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not found |
| 503 | Service unavailable |


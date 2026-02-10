# POST /api/v4/projects/{id}/export_relations

**Resource:** [Project import](../resources/Project-import.md)
**Start relations export**
**Operation ID:** `postApiV4ProjectsIdExportRelations`

This feature was introduced in GitLab 14.4

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |

## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 202 | Accepted |
| 400 | Bad request |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not found |
| 503 | Service unavailable |


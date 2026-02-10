# GET /api/v4/bulk_imports

**Resource:** [Imports](../resources/Imports.md)
**List all GitLab Migrations**
**Operation ID:** `getApiV4BulkImports`

This feature was introduced in GitLab 14.1.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `page` | query | integer | No | Current page number |
| `per_page` | query | integer | No | Number of items per page |
| `sort` | query | enum: asc, desc | No | Return GitLab Migrations sorted in created by `asc` or `desc` order. |
| `status` | query | enum: created, started, finished... | No | Return GitLab Migrations with specified status |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | Unauthorized |
| 404 | Not found |
| 503 | Service unavailable |

**Success Response Schema:**

[APIEntitiesBulkImport](../schemas/APIEntitiesBulkImport/APIEntitiesBulkImport.md)


# GET /api/v4/bulk_imports/entities

**Resource:** [Imports](../resources/Imports.md)
**List all GitLab Migrations' entities**
**Operation ID:** `getApiV4BulkImportsEntities`

This feature was introduced in GitLab 14.1.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `page` | query | integer | No | Current page number |
| `per_page` | query | integer | No | Number of items per page |
| `sort` | query | enum: asc, desc | No | Return GitLab Migrations sorted in created by `asc` or `desc` order. |
| `status` | query | enum: created, started, finished... | No | Return all GitLab Migrations' entities with specified status |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | Unauthorized |
| 404 | Not found |
| 503 | Service unavailable |

**Success Response Schema:**

[APIEntitiesBulkImportsEntity](../schemas/APIEntitiesBulkImportsEntity/APIEntitiesBulkImportsEntity.md)


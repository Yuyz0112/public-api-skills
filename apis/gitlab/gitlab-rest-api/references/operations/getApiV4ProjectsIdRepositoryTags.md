# GET /api/v4/projects/{id}/repository/tags

**Resource:** [Tags](../resources/Tags.md)
**Get a project repository tags**
**Operation ID:** `getApiV4ProjectsIdRepositoryTags`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `sort` | query | enum: asc, desc | No | Return tags sorted in updated by `asc` or `desc` order. |
| `order_by` | query | enum: name, updated, version | No | Return tags ordered by `name`, `updated`, `version` fields. |
| `search` | query | string | No | Return list of tags matching the search criteria |
| `page_token` | query | string | No | Name of tag to start the pagination from |
| `page` | query | integer | No | Current page number |
| `per_page` | query | integer | No | Number of items per page |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 403 | Unauthenticated |
| 404 | Not found |
| 422 | Unprocessable entity |
| 503 | Service unavailable |

**Success Response Schema:**

[APIEntitiesTag](../schemas/APIEntitiesTag/APIEntitiesTag.md)


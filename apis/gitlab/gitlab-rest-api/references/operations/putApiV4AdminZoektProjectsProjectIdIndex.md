# PUT /api/v4/admin/zoekt/projects/{project_id}/index

**Resource:** [Code search](../resources/Code-search.md)
**Triggers indexing for the specified project**
**Operation ID:** `putApiV4AdminZoektProjectsProjectIdIndex`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `project_id` | path | integer | Yes | The id of the project you want to index |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | 401 Unauthorized |
| 403 | 403 Forbidden |
| 404 | 404 Not found |

**Success Response Schema:**

[APIEntitiesSearchZoektProjectIndexSuccess](../schemas/APIEntitiesSearchZoektProjectIndexSuccess/APIEntitiesSearchZoektProjectIndexSuccess.md)


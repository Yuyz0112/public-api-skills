# GET /api/v4/projects/{id}/templates/{type}

**Resource:** [Project templates](../resources/Project-templates.md)
**Get a list of templates available to this project**
**Operation ID:** `getApiV4ProjectsIdTemplatesType`

This endpoint was introduced in GitLab 11.4

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `type` | path | enum: dockerfiles, gitignores, gitlab_ci_ymls... | Yes | The type (dockerfiles|gitignores|gitlab_ci_ymls|licenses|issues|merge_requests) of the template |
| `page` | query | integer | No | Current page number |
| `per_page` | query | integer | No | Number of items per page |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | Unauthorized |
| 404 | Not found |

**Success Response Schema:**

[APIEntitiesTemplatesList](../schemas/APIEntitiesTemplatesList/APIEntitiesTemplatesList.md)


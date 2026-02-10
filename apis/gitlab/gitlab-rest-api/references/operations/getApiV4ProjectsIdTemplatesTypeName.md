# GET /api/v4/projects/{id}/templates/{type}/{name}

**Resource:** [Project templates](../resources/Project-templates.md)
**Download a template available to this project**
**Operation ID:** `getApiV4ProjectsIdTemplatesTypeName`

This endpoint was introduced in GitLab 11.4

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `type` | path | enum: dockerfiles, gitignores, gitlab_ci_ymls... | Yes | The type (dockerfiles|gitignores|gitlab_ci_ymls|licenses|issues|merge_requests) of the template |
| `name` | path | string | Yes | The key of the template, as obtained from the collection endpoint. |
| `source_template_project_id` | query | integer | No | The project id where a given template is being stored. This is useful when multiple templates from different projects have the same name |
| `project` | query | string | No | The project name to use when expanding placeholders in the template. Only affects licenses |
| `fullname` | query | string | No | The full name of the copyright holder to use when expanding placeholders in the template. Only affects licenses |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | Unauthorized |
| 404 | Not found |

**Success Response Schema:**

[APIEntitiesLicense](../schemas/APIEntitiesLicense/APIEntitiesLicense.md)


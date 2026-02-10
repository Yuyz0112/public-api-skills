# POST /api/v4/projects/{id}/pipeline

**Resource:** [Pipelines](../resources/Pipelines.md)
**Create a new pipeline**
**Operation ID:** `postApiV4ProjectsIdPipeline`

This feature was introduced in GitLab 8.14

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The project ID or URL-encoded path |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Created |
| 400 | Bad request |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not found |

**Success Response Schema:**

[APIEntitiesCiPipeline](../schemas/APIEntitiesCiPipeline/APIEntitiesCiPipeline.md)


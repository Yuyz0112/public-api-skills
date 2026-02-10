# POST /api/v4/projects/{id}/pipelines/{pipeline_id}/retry

**Resource:** [Pipelines](../resources/Pipelines.md)
**Retry builds in the pipeline**
**Operation ID:** `postApiV4ProjectsIdPipelinesPipelineIdRetry`

This feature was introduced in GitLab 8.11.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The project ID or URL-encoded path |
| `pipeline_id` | path | integer | Yes | The pipeline ID |

## Responses

| Status | Description |
|--------|-------------|
| 201 | Created |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not found |

**Success Response Schema:**

[APIEntitiesCiPipeline](../schemas/APIEntitiesCiPipeline/APIEntitiesCiPipeline.md)


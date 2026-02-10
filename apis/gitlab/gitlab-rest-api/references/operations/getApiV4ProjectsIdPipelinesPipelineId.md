# GET /api/v4/projects/{id}/pipelines/{pipeline_id}

**Resource:** [Pipelines](../resources/Pipelines.md)
**Gets a specific pipeline for the project**
**Operation ID:** `getApiV4ProjectsIdPipelinesPipelineId`

This feature was introduced in GitLab 8.11

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The project ID or URL-encoded path |
| `pipeline_id` | path | integer | Yes | The pipeline ID |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not found |

**Success Response Schema:**

[APIEntitiesCiPipelineWithMetadata](../schemas/APIEntitiesCiPipelineWithMetadata/APIEntitiesCiPipelineWithMetadata.md)


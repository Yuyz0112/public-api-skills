# GET /api/v4/projects/{id}/pipelines/latest

**Resource:** [Pipelines](../resources/Pipelines.md)
**Gets the latest pipeline for the project branch**
**Operation ID:** `getApiV4ProjectsIdPipelinesLatest`

This feature was introduced in GitLab 12.3

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The project ID or URL-encoded path |
| `ref` | query | string | No | Branch ref of pipeline. Uses project default branch if not specified. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not found |

**Success Response Schema:**

[APIEntitiesCiPipelineWithMetadata](../schemas/APIEntitiesCiPipelineWithMetadata/APIEntitiesCiPipelineWithMetadata.md)


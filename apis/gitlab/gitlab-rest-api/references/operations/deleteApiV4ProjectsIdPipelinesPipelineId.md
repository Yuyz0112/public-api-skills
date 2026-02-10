# DELETE /api/v4/projects/{id}/pipelines/{pipeline_id}

**Resource:** [Pipelines](../resources/Pipelines.md)
**Deletes a pipeline**
**Operation ID:** `deleteApiV4ProjectsIdPipelinesPipelineId`

This feature was introduced in GitLab 11.6

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The project ID or URL-encoded path |
| `pipeline_id` | path | integer | Yes | The pipeline ID |

## Responses

| Status | Description |
|--------|-------------|
| 204 | Pipeline was deleted |
| 403 | Forbidden |


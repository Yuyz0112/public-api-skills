# PUT /api/v4/projects/{id}/pipelines/{pipeline_id}/metadata

**Resource:** [Pipelines](../resources/Pipelines.md)
**Updates pipeline metadata**
**Operation ID:** `putApiV4ProjectsIdPipelinesPipelineIdMetadata`

This feature was introduced in GitLab 16.6

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The project ID or URL-encoded path |
| `pipeline_id` | path | integer | Yes | The pipeline ID |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Bad request |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not found |

**Success Response Schema:**

[APIEntitiesCiPipelineWithMetadata](../schemas/APIEntitiesCiPipelineWithMetadata/APIEntitiesCiPipelineWithMetadata.md)


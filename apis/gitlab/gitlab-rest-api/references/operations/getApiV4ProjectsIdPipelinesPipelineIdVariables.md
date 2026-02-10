# GET /api/v4/projects/{id}/pipelines/{pipeline_id}/variables

**Resource:** [Pipelines](../resources/Pipelines.md)
**Gets the variables for a given pipeline**
**Operation ID:** `getApiV4ProjectsIdPipelinesPipelineIdVariables`

This feature was introduced in GitLab 11.11

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

[APIEntitiesCiVariable](../schemas/APIEntitiesCiVariable/APIEntitiesCiVariable.md)


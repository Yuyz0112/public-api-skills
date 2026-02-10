# GET /api/v4/projects/{id}/pipelines/{pipeline_id}/jobs

**Resource:** [Pipelines](../resources/Pipelines.md)
**Get pipeline jobs**
**Operation ID:** `getApiV4ProjectsIdPipelinesPipelineIdJobs`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The project ID or URL-encoded path |
| `pipeline_id` | path | integer | Yes | The pipeline ID |
| `include_retried` | query | boolean | No | Includes retried jobs |
| `scope` | query | any | No | The scope of builds to show |
| `page` | query | integer | No | Current page number |
| `per_page` | query | integer | No | Number of items per page |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not found |

**Success Response Schema:**

[APIEntitiesCiJob](../schemas/APIEntitiesCiJob/APIEntitiesCiJob.md)


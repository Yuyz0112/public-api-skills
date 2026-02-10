# GET /api/v4/projects/{id}/pipeline_schedules/{pipeline_schedule_id}/pipelines

**Resource:** [Pipeline schedules](../resources/Pipeline-schedules.md)
**Get all pipelines triggered from a pipeline schedule**
**Operation ID:** `getApiV4ProjectsIdPipelineSchedulesPipelineScheduleIdPipelines`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `page` | query | integer | No | Current page number |
| `per_page` | query | integer | No | Number of items per page |
| `pipeline_schedule_id` | path | integer | Yes | The pipeline schedule ID |
| `scope` | query | enum: running, pending, finished... | No | The scope of pipelines |
| `status` | query | enum: created, waiting_for_resource, preparing... | No | The status of pipelines |
| `updated_before` | query | string (date-time) | No | Return pipelines updated before the specified datetime. Format: ISO 8601 YYYY-MM-DDTHH:MM:SSZ |
| `updated_after` | query | string (date-time) | No | Return pipelines updated after the specified datetime. Format: ISO 8601 YYYY-MM-DDTHH:MM:SSZ |
| `created_before` | query | string (date-time) | No | Return pipelines created before the specified datetime. Format: ISO 8601 YYYY-MM-DDTHH:MM:SSZ |
| `created_after` | query | string (date-time) | No | Return pipelines created after the specified datetime. Format: ISO 8601 YYYY-MM-DDTHH:MM:SSZ |
| `sort` | query | enum: asc, desc | No | Sort pipelines |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not found |

**Success Response Schema:**

[APIEntitiesCiPipelineBasic](../schemas/APIEntitiesCiPipelineBasic/APIEntitiesCiPipelineBasic.md)


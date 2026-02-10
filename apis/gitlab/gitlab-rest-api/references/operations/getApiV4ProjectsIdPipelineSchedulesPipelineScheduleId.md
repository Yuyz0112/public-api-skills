# GET /api/v4/projects/{id}/pipeline_schedules/{pipeline_schedule_id}

**Resource:** [Pipeline schedules](../resources/Pipeline-schedules.md)
**Get a single pipeline schedule**
**Operation ID:** `getApiV4ProjectsIdPipelineSchedulesPipelineScheduleId`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `pipeline_schedule_id` | path | integer | Yes | The pipeline schedule id |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not found |

**Success Response Schema:**

[APIEntitiesCiPipelineScheduleDetails](../schemas/APIEntitiesCiPipelineScheduleDetails/APIEntitiesCiPipelineScheduleDetails.md)


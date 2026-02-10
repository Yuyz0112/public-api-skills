# POST /api/v4/projects/{id}/pipeline_schedules/{pipeline_schedule_id}/take_ownership

**Resource:** [Pipeline schedules](../resources/Pipeline-schedules.md)
**Take ownership of a pipeline schedule**
**Operation ID:** `postApiV4ProjectsIdPipelineSchedulesPipelineScheduleIdTakeOwnership`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `pipeline_schedule_id` | path | integer | Yes | The pipeline schedule id |

## Responses

| Status | Description |
|--------|-------------|
| 201 | Created |
| 400 | Bad request |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not found |

**Success Response Schema:**

[APIEntitiesCiPipelineScheduleDetails](../schemas/APIEntitiesCiPipelineScheduleDetails/APIEntitiesCiPipelineScheduleDetails.md)

